# MongoDB Server Version Compatibility

Mongoose relies on the [MongoDB Node.js Driver](http://mongodb.github.io/node-mongodb-native/) to talk to MongoDB. 
You can refer to [this table](https://docs.mongodb.com/ecosystem/drivers/driver-compatibility-reference/#node-js-driver-compatibility) for up-to-date information as to which version of the MongoDB driver supports which version of MongoDB.

Below are the [semver](http://semver.org/) ranges representing which versions of mongoose are compatible with the listed versions of MongoDB server.

* MongoDB Server 2.4.x: mongoose `^3.8` or `4.x`
* MongoDB Server 2.6.x: mongoose `^3.8.8` or `4.x`
* MongoDB Server 3.0.x: mongoose `^3.8.22`, `4.x`, or `5.x`
* MongoDB Server 3.2.x: mongoose `^4.3.0` or `5.x`
* MongoDB Server 3.4.x: mongoose `^4.7.3` or `5.x`
* MongoDB Server 3.6.x: mongoose `5.x`
* MongoDB Server 4.0.x: mongoose `^5.2.0`
* MongoDB Server 4.2.x: mongoose `^5.7.0`
* MongoDB Server 4.4.x: mongoose `^5.10.0`

Note that Mongoose 5.x dropped support for all versions of MongoDB before 3.0.0. If you need to use MongoDB 2.6 or older, use Mongoose 4.x.

## Further Reading

Are you on Mongoose 3.x and looking to migrate to 4.x? Check out [_Moving Forward with Mongoose.js_ on Pluralsight](https://pluralsight.pxf.io/c/1321469/424552/7490?u=https%3A%2F%2Fapp.pluralsight.com%2Flibrary%2Fcourses%2Fmongoosejs-moving-forward%2Ftable-of-contents).
This video course walks you through the new features and backwards breaking changes in Mongoose 4, so you can upgrade with confidence.