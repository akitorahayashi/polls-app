## Overview

This is a simple Diango voting app.

The reusable `polls` app is located in the `src/polls` directory. If you want to use it in another project, you can install it directly from this repository.

## Development Environment Setup

1.  **Install dependencies**

    ```bash
    poetry install
    ```

2.  **Run database migrations**

    ```bash
    poetry run python manage.py migrate
    ```

3.  **Start the development server**

    ```bash
    poetry run python manage.py runserver
    ```

    You can access the polls app at `/polls/`.

4.  **Run tests**

    ```bash
    poetry run pytest
    ```
