# AI-SQL-Agent

AI-SQL-Agent is an AI-powered tool that converts plain English questions into SQL queries and executes them to return the results. It is built using N8N and PostgreSQL, aiming to simplify database interactions by automating SQL query generation.

## Features
- Plain-English to SQL: Convert plain English questions into SQL queries without writing any code.
- Contextual Memory: Remembers context such as filters, dates, and previous queries to provide accurate results.
- PostgreSQL Integration: Interacts with PostgreSQL databases to run queries directly on your data.
- Query Execution: Executes the generated SQL query and returns the results in a single line.

## How It Works
- Google Gemini Chat Model: Understands plain English questions and decides how to respond.
- Simple Memory: Retains context like previous queries, filters, and dates for accurate responses.
- PostgreSQL: Analyzes the database schema to determine the structure and availability of data.
- Query Executor: Runs the SQL query and returns the result in a concise format.

## Benefits
- Efficiency: Saves time by automating SQL query generation and execution.
- Ease of Use: No need to manually write SQL queries—just ask a question in English.
- Fast Insights: Get data insights quickly with minimal effort.

## Workflow Template 
Below are the key N8N workflow template files used for the project that automate the process:

- [SQL Agent.json](https://github.com/AlishaMahanty/AI-SQL-Agent/blob/main/N8N_Workflow_Template/SQL%20Agent.json): Configuration for the AI SQL agent.
- [sql_query_executor.json](https://github.com/AlishaMahanty/AI-SQL-Agent/blob/main/N8N_Workflow_Template/sql_query_executor.json): Defines the SQL query execution logic.
