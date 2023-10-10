# Using MongoDB for Information Storage

* Status: proposed
* Deciders: James
* Date: 2023-10-10

---
## Context and Problem Statement

What can we use to store the different restaurant menus, as well as customer reviews and inventory information?

Our app will need to access a server-side database system in order to save and access information such as what is on offer at a given restaurant as well as how customers have perceived their service quality. 

## Decision Drivers 

* expandability as app grows
* able to handle complex queries
* fast data retrieval

## Considered Options

* MongoDB
* MySQL

## Decision Outcome

Chosen option: "MongoDB"

MongoDB was chosen as it provides a scalable low cost solution with built in database monitoring tools to maintain data validity. 

### Positive Consequences 

* can scale as app reach grows
* multi-cloud storage solutions
* decreased cost through serverless solutions

### Negative Consequences 

* steep learning curve as dev team hasn't worked with MongoDB before
* data validation will be necessary to ensure the database is kept accurate

# Links

* [MongoDB](https://www.mongodb.com/)