# SQL Tool Usage In Agentic AI
A simple demonstration of using SQL tools in an agentic AI context. Includes a Jupyter notebook and requirements for reproducibility. This project seeks to explore how SQL tools can be embedded in agentic AI workflows — for example, enabling an intelligent agent to query, update or manage a SQL database programmatically as part of its actions.

## Files
- `sql_tool_usage.ipynb` — interactive notebook showing how SQL tools are integrated.  
- `requirements.txt` — Python dependencies needed to run the notebook.  

## Setup
1. Clone the repository:  
   ```bash
   git clone https://github.com/manish-ch0pra/SQL-Tool-Usage-In-Agentic-AI.git
   cd SQL-Tool-Usage-In-Agentic-AI

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Replace your OpenAI API key in the script:
    ```python
    openai.api_key = "<replace-with-your-api-key>"
    ```

4. Run the notebook
    ```bash
    jupyter notebook sql_tool_usage.ipynb
    ```