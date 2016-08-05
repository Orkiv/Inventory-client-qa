# Additional Document
The aim of this document is to provide more insight on API endpoint paths

### /items/count/

To add price constraints, add the keys : `minprice` and `maxprice`, which are reserved for such functionality, to your request's query parameter.

#### Sample query dictionary

InventoryClient-Dictionary
		
		{ minprice: integer, maxprice: integer }
		
### /items/ or /items/?allfields

To get only one item set the key `open` within your request dictionary. Only set this key as any additional keys will be checked during the request.

InventoryClient-Dictionary

#### Sample query dictionary

		{ open : "<item id>" }
