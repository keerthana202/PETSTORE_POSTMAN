📍The Swagger Petstore API (v1.0.7, OAS 2.0) provides a sample pet store system with endpoints for managing pets, orders, and users.

📍Store Module – Order Management

This module handles pet store orders and inventory:

    ● GET /store/inventory → Retrieves the current pet inventory by status.

    ● POST /store/order → Places an order for a pet.

    ● GET /store/order/{orderId} → Fetches order details by ID.

    ● DELETE /store/order/{orderId} → Cancels an order by ID.

Authorization requires an API key (special-key). The API follows RESTful principles and is widely used for testing in Swagger UI and Postman.
