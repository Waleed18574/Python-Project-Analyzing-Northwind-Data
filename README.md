# Python-Project-Analyzing-Northwind-Data (In Progress)

## Data Dictionary

## Data Dictionary

## products
| Column Name     | Data Type | Description                                    |
|-----------------|-----------|------------------------------------------------|
| ProductName     | String    | Name of the product                            |
| SupplierID      | Integer   | Unique identifier for the supplier             |
| CategoryID      | Integer   | Unique identifier for the category             |
| QuantityPerUnit | String    | Quantity of the product per unit               |
| UnitPrice       | Float     | Price per unit of the product                  |
| UnitsInStock    | Integer   | Number of units currently in stock             |
| UnitsOnOrder    | Integer   | Number of units currently on order             |
| ReorderLevel    | Integer   | Minimum number of units before reorder         |
| Discontinued    | Boolean   | Indicates if the product is discontinued (TRUE/FALSE) |

### categories
| Column Name  | Data Type | Description                                    |
|--------------|-----------|------------------------------------------------|
| CategoryName | String    | Name of the category                           |
| Description  | String    | Description of the category                    |

### orders
| Column Name    | Data Type | Description                                    |
|----------------|-----------|------------------------------------------------|
| OrderID        | Integer   | Unique identifier for the order                |
| CustomerID     | String    | Unique identifier for the customer             |
| EmployeeID     | Integer   | Unique identifier for the employee             |
| OrderDate      | Date      | Date when the order was placed                 |
| RequiredDate   | Date      | Date by which the order is required            |
| ShippedDate    | Date      | Date when the order was shipped                |
| ShipVia        | Integer   | Shipping method identifier                     |
| Freight        | Float     | Freight cost for the order                     |
| ShipName       | String    | Name of the shipper                            |
| ShipAddress    | String    | Shipping address                               |
| ShipCity       | String    | Shipping city                                  |
| ShipRegion     | String    | Shipping region                                |
| ShipPostalCode | String    | Shipping postal code                           |
| ShipCountry    | String    | Shipping country                               |

### order_details
| Column Name | Data Type | Description                                    |
|-------------|-----------|------------------------------------------------|
| OrderID     | Integer   | Unique identifier for the order                |
| ProductID   | Integer   | Unique identifier for the product              |
| UnitPrice   | Float     | Price per unit of the product at the time of the order |
| Quantity    | Integer   | Quantity of the product ordered                |
| Discount    | Float     | Discount applied to the product                |


### locations
| Column Name   | Data Type | Description                                      |
|---------------|-----------|--------------------------------------------------|
| CustomerID    | String    | Unique identifier for the customer               |
| Country       | String    | Country where the customer is located            |



