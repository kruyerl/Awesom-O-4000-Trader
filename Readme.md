## Traderator9000

# Objective
develope a trading robot, that will be able to do the following:
1- Stream real time "quotes"
2- Place "enter and exit positions"
3- Manage account data ("orders, poitions & activity")
4- Calculate different "technical indicators"

# Goals
- Learn python
- Learn OOP

# Breaking down the Solution
- Robot
    - Handles the interaction with the TD Ameritrade API. Makes any request related to the TD API. Represents the "highest level of the heirarchy".
- Stock Frame
    - Stores all the "price data". Used to add "indicators". Handles the "appending", organising and deleting of data.
- Portfolio
    - Represents a trading portfolio of multiple positions. Will be used to calculate common portfolio metrics and be used to answer general questions about our positions as we trade.
- Trade 
    - A trade which will represent an order to be placed. Functionality related to modifying different aspects of an order.
- Indicators
    - A technical indicator to be used during trading. Specifies the buy/sell criteria, and any methodology used for calculation.
