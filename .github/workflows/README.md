# GitHub Actions Workflows

This directory contains GitHub Actions workflows for the Graphiant SDK Python package.

## Workflows

### `lint.yml` - Code Quality Checks
Comprehensive linting workflow that runs multiple code quality checks in parallel:
- **Flake8** - Python style guide (PEP 8) and code quality checks
- **MyPy** - Static type checking

### `test.yml` - Testing
Runs all tests for the SDK:
- **`test` job** - Matrix job testing against Python 3.9, 3.10, 3.11, 3.12, 3.13:
  - Unit tests with pytest
  - Code coverage reporting
  - Coverage reports uploaded to Codecov (Python 3.12 only)

### `build.yml` - Build Package
Builds the Python package:
- Creates wheel and source distribution
- Verifies build artifacts were created successfully
- Uploads build artifacts

### `release.yml` - Release and Publish
Publishes the package to PyPI:
- Manual trigger only (workflow_dispatch)
- Restricted to repository admins and maintainers only
- Requires `PYPI_API_TOKEN` secret to be set
- Optional: Can build without publishing (for testing)

## Setup

### Required Secrets

#### For Release Workflow

For the release workflow to publish to PyPI, you need to set up the following secret in GitHub:

1. Go to your repository settings
2. Navigate to **Secrets and variables** → **Actions**
3. Add a new secret:
   - **Name**: `PYPI_API_TOKEN`
   - **Value**: Your PyPI API token (get it from https://pypi.org/manage/account/token/)
   - **Note**: Must be configured as a secret (not a variable) for security

#### Optional Secrets/Variables for Test Workflow

The test workflow can optionally use Graphiant API credentials to run integration tests (e.g., `test_sanity.py`). If these are not configured, credential-dependent tests will be skipped.

To enable integration tests:

1. Go to your repository settings
2. Navigate to **Secrets and variables** → **Actions**
3. Add the following secrets or variables:
   - **Name**: `GRAPHIANT_HOST`
     - **Value**: Your Graphiant API host (e.g., `https://api.graphiant.com`)
     - **Note**: Can be configured as either a secret or a variable
   - **Name**: `GRAPHIANT_USERNAME`
     - **Value**: Your Graphiant API username
     - **Note**: Should be configured as a secret for security
   - **Name**: `GRAPHIANT_PASSWORD`
     - **Value**: Your Graphiant API password
     - **Note**: Must be configured as a secret for security

The workflow will check for these credentials and run integration tests if they are available. If not configured, the workflow will still run but skip credential-dependent tests.

### Workflow Triggers

- **Pull Requests**: All workflows run on PRs to ensure code quality
- **Push to main/develop**: CI workflows run on pushes to main branches
- **Scheduled**: Test workflow runs nightly at 2 AM UTC
- **Manual**: Release workflow must be manually triggered via workflow_dispatch (restricted to admins and maintainers)

## Usage

### Running Workflows Locally

While you can't run GitHub Actions locally, you can run the same commands:

```bash
# Linting
pip install -r requirements.txt
pip install -r test-requirements.txt
flake8 graphiant_sdk/ --count --select=E9,F63,F7,F82 --show-source --statistics
flake8 graphiant_sdk/ --count --exit-zero --max-complexity=10 --max-line-length=127 --statistics
mypy graphiant_sdk/

# Testing
# Without credentials (credential-dependent tests will be skipped)
pytest --cov=graphiant_sdk --cov-report=xml --cov-report=term

# With credentials (for integration tests)
export GRAPHIANT_HOST="https://api.graphiant.com"
export GRAPHIANT_USERNAME="your-username"
export GRAPHIANT_PASSWORD="your-password"
pytest --cov=graphiant_sdk --cov-report=xml --cov-report=term

# Building
pip install build wheel
python -m build

# Publishing (requires PyPI credentials)
pip install twine
twine check dist/*
twine upload dist/*
```

### Publishing a Release

1. Ensure the version in `setup.py` and `pyproject.toml` matches the version you want to publish
2. Manually trigger the release workflow via `workflow_dispatch` from the GitHub Actions tab
3. Provide the package version when prompted (should match setup.py/pyproject.toml)
4. Choose whether to publish to PyPI (default: false, for testing builds)
5. The workflow will build and optionally publish to PyPI

## Workflow Status

You can view workflow status in the **Actions** tab of your GitHub repository.
