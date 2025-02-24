# text-to-sql

**This is a project to translate plain text into SQL statements.**

**The technology used include:**
1. OpenAI for LLM model
2. Langchain for SQL agent
3. mySQL for database

**Future improvements:**
1. Pydantic for structured outputs
2. Langsmith or custom basetool for extracting each thought process (currently uses prompt template to specify expected output)
3. Exploration of free models such as text-to-sql instead of OpenAI
4. Building a streamlit application to provide simple user interface


**Credit goes to this youtuber Pradip Nichite:**

1. https://blog.futuresmart.ai/langchain-sql-agents-openai-llms-query-database-using-natural-language
2. https://youtu.be/VG9KYCS0-8E?feature=shared
