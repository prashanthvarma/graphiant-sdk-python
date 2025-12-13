We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes and ensure they pass local tests:
   ```bash
   # Run linting
   flake8 graphiant_sdk/
   mypy graphiant_sdk/
   
   # Run tests
   pytest --cov=graphiant_sdk
   ```
4. Commit your changes with a clear message (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

**Note**: All pull requests automatically run CI/CD checks (linting, testing across multiple Python versions). Ensure all checks pass before requesting review.
