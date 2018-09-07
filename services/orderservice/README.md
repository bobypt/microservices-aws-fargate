# Order Service

## Build project

 ```npm install```

 ## Start app
 ```npm start```

 Application will start locally and listen on port 8080.

 ## Test
 health url -  ```curl localhost:8080/api/v1/orderservice/health```
 get order details -  ```curl localhost:8080/api/v1/orderservice/orders/875855955```

 ## Build docker image
```docker build -t msdemo/orderservice .```

## Start a container
```docker run -p 8080:8080 --name order-service -t msdemo/orderservice```

## Stop the server
```docker rm -f order-service```