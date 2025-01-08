# Social Media Performance Analysis

A basic analytics module leveraging LangFlow and DataStax to analyze engagement data from mock social media accounts, integrated with a Streamlit-based web application. The application allows users to interact with a LangFlow-generated workflow for analyzing social media performance.

## Used Tools:
● DataStax Astra DB for database operations.

● Langflow for workflow creation and GPT integration.

● Streamlit for frontend access of Langflow.

## Features

- Powered by **LangFlow** and **DataStax** for robust and accurate analysis.
- Interactive chat interface for social media performance analysis.
- Persistent query and response history using Streamlit's `session_state`.
- Easy-to-use interface with real-time insights from LangFlow.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/KunjCode/CyberCreatures.git
cd CyberCreatures
```

### 2. Create a Virtual Environment
Set up a Python virtual environment to manage dependencies:
```bash
python -m venv env

```
Activate the virtual environment:
On Windows:
```bash
source env/Scripts/activate
```
On Mac/Linux:
```bash
source env/bin/activate
```

### 3. Install Dependencies
Install the required Python libraries:

```bash
pip install -r requirements.txt
```
### 4. Create a .env File
Create a .env file in the root directory of your project and add the following:

dotenv
```
APP_TOKEN=<your-langflow-generated-token>
```
Replace <your-langflow-generated-token> with the API token generated by LangFlow.

### 5. Run the Application
Start the Streamlit application:

```bash
streamlit run main.py
```

## How to Use
(1) Enter your query in the text area provided.

(2) Click on the "Generate Insights" button to analyze the query.

View the analysis result along with the chat history displayed below the input area.

## Project Structure
- app.py: Main application file containing the Streamlit app logic.
- requirements.txt: List of dependencies required for the project.
- .env: File for storing environment variables securely.

## Demonstration
https://youtu.be/U3UeG7rihoQ

## Notes
Ensure you have a valid LangFlow APP_TOKEN before running the application.

The API token is stored securely in the .env file and accessed through python-dotenv.
