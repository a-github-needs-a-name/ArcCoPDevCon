## Task of the Day

![](./assets/context.png)

> PoC implementation of service (Python) consuming Cloud Events from Kafka and persist this in a document database (MongoDB)

## Game plan

1. Enable every contributor to develop Python (and ease documentation)
   1. Ensure that all use the same Python Version
   2. Find out how to deal with different Python versions, if somebody works in another project
2. Get a test topic on a kafka cluster for development purposes
   1. Ensure every contributor gets an own topic to avoid side effects during development
3. Implement consume messages
4. Get a MongoDB test instance
   1. Ensure every contributor can work with own test data
5. Implement DB write 
