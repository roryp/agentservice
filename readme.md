# Sample Agents 

This sample demonstrates how to use agent operations from the Azure Agents service using a synchronous client.

## Usage

1. **Sign in to Azure CLI**:
   ```sh
   az login --tenant <your-tenant-id>
   ```

2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Set these environment variables with your own values:
    - `PROJECT_CONNECTION_STRING`: The project connection string, as found in the overview page of your Azure AI Foundry project.
    -  MODEL DEPLOYMENT : gpt-4o

4. Run the samples:
    ```
    python sample_agents_code_interpreter.py
    python sample_agents_basics.py
    python sample_agents_openapi.py
    ```
