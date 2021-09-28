# 09-28-21

## Today's Agenda
- Intro to MongoDB
- Intro to Mongoose

### Mongo Commands

#### View all databases
> show dbs

#### Switch/Create to database
> use users_db

#### Retrieve all data from collection
> db.users.find({ "name": "John Doe" })

#### Create one instance in a collection
> db.users.insert({ ...properties })

#### Create multiple instances in a collection
> db.users.insertMany([ ...objects ])

#### Update a property on an instance
> db.users.update({ ...conditions }, { $set: { ...values } })

#### Add data to an array on an instance
> db.users.update({ ...conditions }, { $push: { <array_name>: <new_value> } })

#### Delete an instance from a collection
> db.users.remove({ ...conditions })