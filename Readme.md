## Traderator9000

# Objective
develope a trading robot, that will be able to do the following:
- Stream real time "quotes"
- Place "enter and exit positions"
- Manage account data ("orders, poitions & activity")
- Calculate different "technical indicators"

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
