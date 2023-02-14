# glowing-potato
# MongoDB Methods
 - The [.mapReduce()](https://www.mongodb.com/docs/manual/reference/method/db.collection.mapReduce/#mongodb-method-db.collection.mapReduce) collection method allows you to narrow down what you're searching for in a large data set.
- The [.dropDatabase()](https://www.mongodb.com/docs/manual/reference/method/db.dropDatabase/#mongodb-method-db.dropDatabase) database method deletes the current database and all the associated files in it.
- The [.dropAllUsers()](https://www.mongodb.com/docs/manual/reference/method/db.dropAllUsers/#mongodb-method-db.dropAllUsers) user management method deletes all users and their information (kind of cool, yet scary if you lost all that info). 
 - The [.insertMany](https://www.mongodb.com/docs/manual/reference/method/db.collection.insertMany/#mongodb-method-db.collection.insertMany) collection method inserts multiple documents into a collection.
 - The [.enableAutoSplit()](https://www.mongodb.com/docs/manual/reference/method/sh.enableAutoSplit/#mongodb-method-sh.enableAutoSplit) sharding method auto-splits a sharded cluster.
- The [.splitAt()](https://www.mongodb.com/docs/manual/reference/method/sh.splitAt/#mongodb-method-sh.splitAt) sharding command splits a chunk at the shard key.

# What is a Shard?
 After those last two methods, you're probably wondering what is a shard? According to the MongoDB glossary, a shard is a single mongod instance or replica set that stores some portion of a sharded cluster's total data set. An example of a shard is pictured below. The picture is from the MongoDB official website.


![image](https://user-images.githubusercontent.com/87744145/218638613-be35fd77-7e51-49d5-902e-15ec512a851b.png)
