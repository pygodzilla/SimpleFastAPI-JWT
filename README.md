# FastAPI Production-Level API with JWT Authentication

This project is a simple demonstration of how to build a production-level API using FastAPI with JSON Web Token (JWT) authentication.

## Overview

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints. It's easy to use, easy to learn, and highly efficient. JSON Web Tokens (JWT) are an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

In this project, we'll create a FastAPI application that includes JWT-based authentication to secure our endpoints.

## Features

- **FastAPI**: Utilizing the power of FastAPI for efficient API development.
- **JWT Authentication**: Implementing JWT-based authentication to secure endpoints.
- **Production Ready**: Demonstrating best practices for building a production-level API.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/pygodzilla/SimpleFastAPI-JWT.git
    cd SimpleFastAPI-JWT
    ```

2. Install dependencies:

    ```bash
    python3 -m venv .pyenv
    source .pyenv/bin/activate
    pip3 install -r requirements.txt
    ```

## Usage

1. Run the FastAPI application:

    ```bash
    uvicorn main:app --reload
    ```

2. Access the API documentation at [http://localhost:8000/docs](http://localhost:8000/docs) to explore available endpoints and interact with them.


## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the GPL-3 License - see the [LICENSE](LICENSE) file for details.
