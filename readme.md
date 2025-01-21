# Sample Agents Code Interpreter

This sample demonstrates how to use agent operations with code interpreter from the Azure Agents service using a synchronous client.

## Usage

1. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

2. Set these environment variables with your own values:
    - `PROJECT_CONNECTION_STRING`: The project connection string, as found in the overview page of your Azure AI Foundry project.
    - `MODEL_DEPLOYMENT_NAME`: The deployment name of the AI model, as found under the "Name" column in the "Models + endpoints" tab in your Azure AI Foundry project.

3. Run the sample:
    ```
    python sdk/ai/azure-ai-projects/samples/agents/sample_agents_code_interpreter.py
    ```
