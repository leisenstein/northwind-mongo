## Northwind@MongoDB ##

### What it is

* Just a simple data dump from SQL's Northwind database to a CSV
* CSV (northwind.csv) turned into multiple CSVs
* CSVs imported into Mongo (mongo-import.sh)


### What it needs

* There aren't any employee/product images
* It's a straight data dump - no relations or special magic


Thanks to [@shayden](https://github.com/shayden) for the csv dump. Buyer beware, caveat emptor, carthago delenda est et al



## Collections To Create

### Employees
* Has Territories []

### Customers
* Has Order []


### Orders
* Has Order-Details []
* Has CustomerID
* Has EmployeeID
* Has ShipperID "ShipVia"


### Order-Details
* Has OrderID
* Has ProductID


### Products
* Has SupplierID
* Has CategoryID


### Territories
* Has RegionID






