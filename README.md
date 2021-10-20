# Coffeeshop Deployment

:warning: This is mainly use for OpenShift GitOps, shouldn't be modified directly

Deployment manifest to deploye the Coffee Shop application.

The apps contains:

* [Coffee Shop UI](https://github.com/froberge/coffeeshop-ui/tree/product-page)
* [Product Service](https://github.com/froberge/product-service/tree/working_code)
* PostgresSQL Database


## Instanciate the database schema
Once the database instance is deployed inside you openShift connect to it in order to create the required schema. Find the script [here](https://github.com/froberge/coffeeshop-documentation/tree/master/dbscripts/product-schema)