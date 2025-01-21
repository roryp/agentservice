# Sample Agents Code Interpreter

This sample demonstrates how to use agent operations with code interpreter from the Azure Agents service using a synchronous client.

## Usage

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

2. Set these environment variables with your own values:
    - `PROJECT_CONNECTION_STRING`: The project connection string, as found in the overview page of your Azure AI Foundry project.
    -  MODEL DEPLOYMENT : gpt-4o

3. Run the sample:
    ```
    az login (I login to a custom tenant with az login --tenant xxxxxxx)
    python sample_agents_code_interpreter.py
    ```
