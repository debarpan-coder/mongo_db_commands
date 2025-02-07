# Mongo Db Commands
___
## Structure Comparison

| Relational DB | Mongo DB |
| --- | --- |
| Database | Database |
| Table | Collection |
| Row | Document |
| Column | Feild |
---
## Starting MongoDB
> ### Start MongoDB Server
> + Open CMD and type the below code to start the MongoDB server.
> ``` cmd
> mongod
> ```

> ### Start MongoDB shell
> + Open CMD and type the below to run MongoDB shell.
> ``` cmd
> mongo
> ```
---
## MongoDB Queries
>  ### Show all databases
> ``` cmd
> show dbs
> ```

> ### To create or use a database
> ``` cmd
> use <databasename>
> ```

> ### To insert a single document(row) in collection(Table). Collection will be created if does not exsist.
> ``` cmd
> db.collection('<collection name>').insertOne(
>   {<json format data eg. name:"ABC", age:22, blood_group : "B+">}
> );
> ```

> ### To insert a many document(row).
> ``` cmd
> db.collection('<collection name>').insertMany([
>   {<json format data eg. name:"ABC", age:22, blood_group : "B+">},
>   {<json format data eg. name:"XYZ", age:20, blood_group : "AB">},   
>   {<json format data eg. name:"PQR", age:23, blood_group : "O">}   
> ]);
> ```
>

> 