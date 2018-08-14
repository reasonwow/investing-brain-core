# investing-brain-core
Platform for investing advice. This is a open source project, and the data source is IEX API(https://iextrading.com/developer/), which is free. 

# Description:
A full stack project that helps me to find best approach to invest my money. 

# Use cases:
1. Give suggestions for portfolio based on the daily stats.
2. Record the purchase history and monitor the portfolio

# Architecture:
TBD - Need to choose the framework for backend and frontend

Backend: Java or Go?

Use Go to implement RESTful API. While I am still considering to use Java Spring Batch Job to generate recommended stocks.

Frontend: React

Database: Relational?

# Phase 1
System Design: 
  Go + React without DB for now.
  
  For now, I think it will be fun to use Go as backend language. If the project becomes more heightweight, might need to migrate some services to Java. Choose IEX API for data source for now. It's free and easy to use. 
  
# Data Source
IEX API - https://iextrading.com/developer/
