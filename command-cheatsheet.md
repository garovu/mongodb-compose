# MongoDB Command Line Cheatsheet

## Connect to MongoDB

To connect to MongoDB, use the following command:

```shell
    mongosh
```

## Show Databases

To show all the databases in MongoDB, use the following command:

```shell
    show dbs
```

## Use a Database

To switch to a specific database, use the following command:

```js
    use <database_name>
```

## Show Collections

To show all the collections in the current database, use the following command:

```js
    show collections
```

## Insert Documents

To insert documents into a collection, use the following command:

```js
    db.<collection_name>.insert(<document>)
```

## Find Documents
To find documents in a collection, use the following command:
```
db.<collection_name>.find(<query>)
```

## Update Documents
To update documents in a collection, use the following command:
```
db.<collection_name>.update(<query>, <update>)
```

## Delete Documents
To delete documents from a collection, use the following command:
```
db.<collection_name>.remove(<query>)
```

## Exit MongoDB Shell
To exit the MongoDB shell, use the following command:
```
exit
```
