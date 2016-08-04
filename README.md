# Additional Document
The aim of this document is to provide more insight on API endpoint paths

### /items/count/

To add price constraints, add the keys : `minprice` and `maxprice`, which are reserved for such functionality, to requests query

#### Sample query

InventoryClient-Dictionary
		
		{ minprice: integer, maxprice: integer }