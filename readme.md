# LearningMongoDB

Follow along files for the Lynda/LinkedIn Learning Course, "Learning MongoDB"


You must add the required databases for the JavaScript files to work as intended within the mondoDB environment
You can do that with the following command. You should have a server running using

```
mongod
```

```
mongoimport --db learning_mongo --collection tours --jsonArray --file tours.json
```

The you may start the mongo environment from your terminal/cmd, and swap into the learning database with:

```
use learning_mongo
```
