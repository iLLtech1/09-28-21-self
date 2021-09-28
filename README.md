# 09-28-21

## Today's Agenda
- Intro to MongoDB
- Intro to Mongoose

### Mongo Commands

#### View all databases
> show dbs

#### Switch to database
> use users_db

#### Retrieve all data from collection
> db.users.find({ "name": "John Doe" })

#### Create one instance in a collection
> db.users.insert()

#### Create multiple instances in a collection
> db.users.insertMany()