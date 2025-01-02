# Data-Driven-ChatBot
 Objective
 1. EDA Module:
 o Develop an EDA module that can handle datasets with rows ranging from (18207, 18).
 o The module should:
  
Automatically analyze any dataset passed to it.
  
Generate acomprehensive EDA report with as many insights as
 possible.
 2. Chatbot for Data Insights:
 o Use the pre-generated EDA report as the knowledge base for the chatbot.
 o The chatbot should:
  
Answer questions about the dataset based on the EDA report.
 3. Mathematical Query Module:
 o Integrate a mathematical functionality into the chatbot so it can answer
 queries like:
  
"What is the difference between the highest and second-highest
 value in column X?"
  
"Whatisthe standard deviation of column Y?"
  
"Calculate the sum of values in column Z greater than 100."
 4. LLM Data Querying:
 o Implement a functionality that allows the chatbot to query a Pandas
 Data Frame or SQL database for specific answers.
 o Example queries:
  
"Showme the top 5 rows where column X>50."
  
"What is the maximum value in column Y?"
