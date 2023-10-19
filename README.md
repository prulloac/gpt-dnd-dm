# GPT-DnD-DM

## Setup

1. Run development environment from .devcontainer
2. Create virtual environment by running the following command:
    ```
    python -m venv openai-env
    ```
3. Activate the virtual environment by running the following command:
    ```
    source openai-env/bin/activate
    ```
4. Install the OpenAI library by running the following command:
    ```
    pip install openai
    ```
5. Set OpenAI API key on a .env file in the root directory of the project:
    ```
    OPENAI_API_KEY=<your-api-key>
    ```
6. Make sure to include the .env file and openai-env directory in the .gitignore file
    ```
    .env
    openai-env/
    ```
