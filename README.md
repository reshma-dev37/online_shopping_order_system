# online_shopping_order_system

This is a simple C++ project that simulates an online order system.  
It demonstrates basic Object-Oriented Programming concepts such as:

- Classes & Objects  
- Encapsulation  
- Header files and implementation files  
- Simple order processing logic  


- Methods: setCustomerDetails(), displayCustomer()

## Customer
- Stores customer details  
- Member variables: name, address, phone  
- Methods: setCustomerDetails(), displayCustomer()

##  product
- Stores product details  
- Member variables: productName, price, quantity  
- Methods: setProductDetails(), calculateTotal()

## Discount
- Handles discount logic  
- Member variables: discountPercent  
- Methods: setDiscount(), applyDiscount()

## Order
- Combines Customer, Product, and Discount  
- Member variables: orderId, finalAmount  
- Methods: setOrderId(), setCustomer(), setProduct(), setDiscount(), processOrder(), displayOrderSummary()

