# SmartSQLer

## Overview
This project redefines database interactions by transforming natural language queries into SQL commands, enabling users to communicate with databases effortlessly. By simply inputting plain English queries, users receive the corresponding SQL commands and the resulting data in an easily understandable text format.  


# Features - 

1. Real-Time Data Interaction and Visualization: Executes SQL commands in real-time, instantly displaying results and reducing amount required to write and develop SQL queries
2. User-Friendly Interface and Advanced Analytics: Features an intuitive dashboard with query history, customizable templates, and complex query support.

# Usage - 

Input: Users provide a natural language query as input to the system front-end

Backend Architecture: The Model used to enable the conversion of Text queries to SQL is Google Gemini - which takes the human-like queries and creates SQL Queries which are then passed to the database involved
and returns the result. 

Output: The Output of the SQL is then passed to the front-end interface
