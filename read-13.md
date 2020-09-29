# Summary of reading for Class-13

## [Mongo Aggregations](https://docs.mongodb.com/manual/core/aggregation-pipeline/)
The aggregation pipeline is a framework for data aggregation modeled for data processing pipelines. Documents enter a multi-stage pipeline that will aggregate the results.

### aggregations are a way to create data based on your data!

* pipeline expressions - operate on teh current document in the pipeline, they cannot refer to data from other documents.
  *  expressions are stateless

## [Aggregation by Example](https://www.compose.com/articles/aggregations-in-mongodb-by-example/)

` db.customers.aggregate([ ... aggregation steps go here ...]);`
* `customers` is the table we are aggregating
* the `aggregate` function takes an array of transformation in order.

### Aggregate Functions
* `$match` - like SQL WHERE clause.
* `$group` - group documents together to perform other transformations and operations on them.
* There are loads more that all do different things.