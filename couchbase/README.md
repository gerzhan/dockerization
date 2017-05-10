Couchbase server
=================

- @see [video tutorila](https://www.youtube.com/watch?v=MtelW_belIA)

## Build in this directory

```bash
$docker build -t custom-couchbase .


## Run docker container

```bash
$docker run -d -p 8091-8093:8091-8093 -e COUCHBASE_ADMINISTRATOR_USERNAME=admin -e COUCHBASE_ADMINISTRATOR_PASSWORD=password -e COUCHBASE_BUCKET=default -e COUCHBASE_BUCKET_PASSWORD= --network="bridge" --name=custom_couchbase_i1 custom-couchbase
``` 