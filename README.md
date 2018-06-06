# Elasticsearch Query Collection

This repository was created with the intent to share my [Postman](https://www.getpostman.com/) collection of queries.

As I learn as much as I can about Elasticsearch's capabilities and API, I plan on updating this collection with all kinds of complex queries.

In order to use this collection:

1. Download and install [Postman](https://www.getpostman.com/) (If you already have it, make sure it is compatible with collection format 2.1 as this is the one I'm using).
2. Clone this repository or download `Elasticsearch API Guide.postman_collection.json`.
3. Open Postman and click the `Import` button. In the next screen, point to the collection file. By selecting the file, it will be imported into your workspace.
4. To make it easier to reuse the collection, I use a variable called `ELASTICSEARCH` which should point to the Elasticsearch API root. By opening requests you'll see that it points to something like `{{ELASTICSEARCH}}/someindex`. By default, the collection here will always have the variable set to `http://localhost:9200` which is Elasticsearch's default endpoint. If you want to target a different cluster, right click the collection, edit it, go to the `Variables` tab and set the value accordingly.