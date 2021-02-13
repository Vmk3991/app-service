# App Service

This application is developed using Spring Boot, Wiremock , Maven , Java 8

**1. Build and run the app using maven**

```bash
mvn clean install
java -jar target/app-service-1.0.0.jar```

```

BaseURL : http://localhost:8000


1. http://localhost:8000/customer/{cust_id}/order/summary

	i.e http://localhost:8000/customer/cust01/order/summary

This above API Provide Order Summary based on customer Id.

2. http://localhost:8000/order/{order_id}/summary

	i.e http://localhost:8000/order/1/summary

This above API Provide Order Summary based on order Id.

3. http://localhost:8000/order/{order_id}/detail

	i.e http://localhost:8000/order/1/detail

This API Provide Order Details based on order Id.

