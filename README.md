# MyProject

This is a simple Python project that demonstrates a calculator module along with tests.

## Tools Used

- **pytest** for testing.
- **pytest-pylint** for linting.
- **pytest-cov** for coverage reporting.
- **virtualenv** for dependency isolation.

## Setup Instructions

1. **Clone the repository** (if applicable) and navigate to the project directory.
2. **Create and activate a virtual environment:**
    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. **Install dependencies:**
    ```bash
    pip3 install -r requirements.txt
    ```
4. **Run tests:**
    ```bash
    pytest --pylint --cov
    ```