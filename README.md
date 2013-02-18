tCouchbaseOutput
================

Talend component to push data streams to a couchbase cluster.

Prereqs
=============

- Talend Open Studio for Data Integration (5.2.1 or above)

- tCouchbaseConnection: (https://github.com/ronniedada/tCouchbaseConnection)

    A predefined connection connects to couchbase server.

Settings
=============

- Connection: tCouchbaseConnection component which handles the connection to a couchbase cluster.

- Input Schema: this component takes a inflow with key/value as schema:


    **key**: the document key as stored in the couchbase cluster.

    **value**: the entire json document.

- Please refer to tParseJson(https://github.com/ijokarumawak/tParseJSON) for how to work out a json output from a data flow.
