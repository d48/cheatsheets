## start and edit local db

```bash
$ mongod
$ mongo 
```

## start using and creating

```bash
$ show dbs
$ use <mydatabasename>
$ db.collectionName.save(<json document object>)
```

## show collection
```bash
$ db.collectionName.find()
```

## delete documents that match a condition
```bash
$ db.collectionName.remove({'field.name': condition})

# removes all documents where title is blank
$ db.collectionName.remove({'title': ''})

# removes all documents where isValidUser is false
$ db.collectionName.remove({'isValidUser': false})
```

## get count of documents in a collection
```bash
$ db.collectionName.find().count()
```
