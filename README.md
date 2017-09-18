# Module under development.

# couchdb_utilities

Invocation of the module
```
var couchUtils = require('couchdb_utilities');
```

### Core
#### Verify Inputs
#### Validate connection - Source
#### Validate Connection - target
#### Get list of Dbs in the Source

```
console.log( couchUtils.listDatabases( "http://0.0.0.0:5984" ) );
[
    "_replicator",
    "_users",
    "test2"
]
```

#### Check if the view exist
#### Check db in the target
#### Create db in target

### Design Docs
#### Create view
#### Get design Docs in a db
#### Check Views in target
#### Delete design docs in target db
#### Create Design docs in target
