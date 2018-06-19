# Orders Sample Data

In order to test and demonstrate Elasticsearch's capabilities I've generated a mock dataset on [Mockaroo](https://mockaroo.com) simulating car orders from a dealership.

Primarily you can load this test data into Elasticsearch by using the `Bulk insert` query available in the collection. Data is, therefore, also available there without the need to download the json file on this folder.

However, if you prefer to load the data some other way, feel free to use `orders.json`.

All objects on this dataset presents the following structure:

    {
       "order_id":"7012bcd3-5c60-4777-8d1b-6bfd9e5c65a8",
       "customer":{
          "first_name":"Morse",
          "last_name":"Meiklejohn",
          "full_name":"Morse Meiklejohn",
          "email":"mmeiklejohn0@fotki.com",
          "job_title":"Account Coordinator",
          "address":{
             "street_address":"23 Commercial Park",
             "street_name":"Katie",
             "street_number":"3",
             "street_suffix":"Crossing",
             "coordinates":{
                "latitude":-11.8532073,
                "longitude":-75.508016
             }
          }
       },
       "car":{
          "make":"Subaru",
          "model":"Alcyone SVX",
          "year":1995
       },
       "order_amount":"43065.62"
    }
