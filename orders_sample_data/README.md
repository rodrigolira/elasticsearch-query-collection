# Orders Sample Data

In order to test and demonstrate Elasticsearch's capabilities I've generated a mock dataset on [Mockaroo](https://mockaroo.com) simulating car orders from a dealership.

Primarily you can load this test data into Elasticsearch by using the `Bulk insert` query available in the collection. Data is, therefore, also available there without the need to download the json file on this folder.

However, if you prefer to load the data some other way, feel free to use `orders.json`.

All objects on this dataset presents the following structure:

    {
    	"order_id":"ae764cc3-cd1d-4a55-89fb-df14c9e67470",
    	"customer":{
    		"first_name":"Frankie",
    		"last_name":"Barringer",
    		"full_name":"Frankie Barringer",
    		"email":"fbarringer0@freewebs.com",
    		"job_title":"Human Resources Manager",
    		"address":{
    			"street_address":"65 Dixon Point",
    			"street_name":"Superior",
    			"street_number":"27",
    			"street_suffix":"Point",
    			"coordinates":{
    				"latitude":50.8323221,
    				"longitude":25.4566978
    			}
    		}
    	},
    	"car":{
    		"make":"Rolls-Royce",
    		"model":"Phantom",
    		"year":2007
    	}
    }
