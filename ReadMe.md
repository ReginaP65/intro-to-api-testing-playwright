| # |                 Check name                  | Test data |
|::|:-------------------------------------------:|:---------:|
|1| GET order with valid order Id return RC=200 |2|
|2|GET order with invalid order Id return RC=400|15|
|3|PUT order with correct order status return RC=200|OPEN|
|4|PUT order with incorrect order status return RC=400|CLOSED|
|5|PUT order with valid api key return RC=200|1234567890123456|
|6|PUT order with invalid api key return RC=401|12345678|
|7|DELETE order with valid api key return RC=200|1234567890123456
|8|DELETE order with invalid api key return RC=401|123456789|

