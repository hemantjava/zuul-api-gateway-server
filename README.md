#currency-exchange
http://localhost:8002/currency-exchange/from/USD/to/INR
uri -> currency-exchange/from/USD/to/INR
application ->currency-exchange-service
#Zuul
http://localhost:8765/{application}/{uri}
#Example
http://localhost:8765/currency-exchange-service/currency-exchange/from/USD/to/INR