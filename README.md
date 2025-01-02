# Data-Driven-ChatBot
 Objective
 1. EDAModule:
 o DevelopanEDAmodule that can handle datasets withrowsrangingfrom
 hundredstothousands.
 o Themoduleshould:
  
Automatically analyze any dataset passed to it.
  
Generate acomprehensiveEDAreport with as many insights as
 possible.
 2. ChatbotforDataInsights:
 o Usethepre-generatedEDAreport as the knowledge base for the chatbot.
 o Thechatbotshould:
  
Answerquestions about the dataset based on the EDA report.
 3. MathematicalQueryModule:
 o Integrate a mathematical functionality into the chatbot so it can answer
 queries like:
  
"Whatisthe difference between the highest and second-highest
 value in column X?"
  
"Whatisthe standard deviation of column Y?"
  
"Calculate the sum of values in column Z greater than 100."
 4. LLMDataQuerying:
 o Implement afunctionalitythatallo
 wsthechatbottoqueryaPandas
 DataFrameorSQLdatabase for specific answers.
 o Examplequeries:
  
"Showmethetop5rowswherecolumn X>50."
  
"Whatisthe maximum value in column Y?"
