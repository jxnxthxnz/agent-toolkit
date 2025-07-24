# PayPal Agent Toolkit Examples

This example demonstrates how to use the PayPal Agentic Toolkit integrated with OpenAI, LangChain, and CrewAI to manage PayPal transactions through AI-powered applications.


## Prerequisites

Before setting up the workspace, ensure you have the following installed:
- Python 3.11 or higher
- `pip` (Python package manager)
- A PayPal developer account for API credentials

## Installing Dependencies

Set up a Python virtual environment and install the required dependencies:
```bash
# Step 1: Create a virtual environment
python -m venv venv

# Step 2: Activate the virtual environment
source venv/bin/activate  # On macOS/Linux
# For Windows:
# venv\Scripts\activate

# Step 3: Install required dependencies
pip install -r requirements.txt

```

## Environment Setup
Create and configure an .env file in the example directory to set your environment variables:
```env
# OpenAI Configuration
OPENAI_API_KEY=<your_openai_api_key>

# Amazon Bedrock Configuration
AWS_ACCESS_KEY_ID=AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY=AWS_SECRET_ACCESS_KEY

# PayPal Configuration
PAYPAL_CLIENT_ID=<your_paypal_client_id>
PAYPAL_SECRET=<your_paypal_secret>

```
Replace the placeholders (<your_openai_api_key>, <your_paypal_client_id>, etc.) with your actual credentials.

## Running the Example
Navigate to the example directory and execute the assistant application:
```bash
python app.py
```

