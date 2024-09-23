# AiBook
This is a AI system that allows users to analyze data using SQL and DuckDB, a lightning-fast database engine, combined with the power of GPT-4, a large language model

Requirments :  You must install Node.js and Python on your local machine.

---------------Import Database ---------------
1. You must install navicat and xampp to local machine.
2. You have to run xampp and click "start" button of "apache" and "mysql" line.
   It will run and you can show enable port number 3306 that left the "stop" button of "mysql" line.
3. You have to open navicate and import "duckdb.sql" file.
4. You have to create a new mysql connection and create new database named "duckdb"
5. If you click right button when you put "duckdb" database item, you can see "Execute SQL file..." item.
6. If you click this item, you can import mysql file. 

You can modify .env file of backend to your mysql connection details.

--------------- Run frontend -----------------

1. You must copy .env.local file into /frontend location
2. You must run "npm install" by cmd into /frontend location
3. You can run frontend.bat to run frontend.

---------------- Run backend -----------------

1. You must copy .env file into /backend location
2. You must run this command by  "pip install -r requirements.txt"
3. You can run backend.bat to run backend.
4. You can change your OPEN_AI_KEY in ask.py file at 10 line.

--------------- Run datagraph-----------------

1. You must run "yarn add" by cmd into /frontend location
2. If you must install yarn at first, you can run this command. "npm install --global yarn"
3. You can run datagraph.bat to run frontend.
