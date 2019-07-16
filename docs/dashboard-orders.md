---
id: dashboard-orders
title: Orders
---

The Orders section shows you all orders placed through the Saleor system by customers, as well as those created manually by administrators.


## All Orders

The main orders list shows all orders in the system, regardless of status.

![Orders list](assets/dashboard-orders/1.png)

To filter orders, use the drop-down menu and view orders by date or fulfillment status. Sorting by status brings up a second menu from which you can choose Fulfilled, Partially Fulfilled or Unfilled Orders.

![Orders list filters](assets/dashboard-orders/2.jpg)


### Viewing a Specific Order

Click on any order from the list to get the full order details. The order screen contains fields for fulfillment status, payment, customer details, and order history.

![Order details](assets/dashboard-orders/3.jpg)


### Order Fulfillment

Fulfillment means whether an order has been sent to the customer or not. Some orders will only have a single field for Unfulfilled or Fulfilled. Others, as in the example here, will have both fields if parts of the order have been sent but other products are yet to be dispatched. 

![Order fulfillment options](assets/dashboard-orders/4.jpg)


### How to Fulfill an Order

Click [[Fulfill]] in the Unfulfilled field and use the stepper to confirm which products are being send. In the example below, the t-shirt and hoodie are being sent in full, only two from four pairs of plimsolls are being sent, and the juice is not being sent.

Once [[Confirm]] is pressed, the t-shirt and hoodie will move to the ‘Fulfilled’ field, as will two pairs of shoes. The other shoes and the juice will remain Unfulfilled.

Add tracking number for the package in the line below the products if you have one.

> When fulfillment is confirmed, the customer will automatically receive an email with information about the goods that they will receive, including any additional information such as tracking numbers.

![Order fulfillment](assets/dashboard-orders/5.jpg)


### How to Cancel a shipment

- Click the three dots in the top right corner of a fulfilled order.
- Click and confirm cancellation when the pop-up appears. Items will be restocked into the Saleor system.

![Canceling shipment](assets/dashboard-orders/6.jpg)


### Customer details

The customer information in the field to the right of the screen on a specific order is automatically generated when the customer completes a transaction. The billing and shipping addresses can be edited if necessary. There is also an option to directly contact the customer via email by clicking on the web address shown in the contact information section.


### Payments

There are three different payment fields:


#### Unpaid Orders

A traditional credit card or bank payment that is awaiting authorization from the bank. Unpaid amounts are listed as ‘pre-authorized’. Once funds are released, the order status will automatically change to fully paid.	

![Unpaid order](assets/dashboard-orders/7.jpg)


#### Fully Paid Orders

Can be fully or partially refunded if there is an issue with the goods or customer service.

- Click on [[Refund]] in the bottom right corner of the box 
- Click [[Confirm]] to refund the full amount. 
- For partial refunds, input the amount or use the stepper to set the amount, then confirm.

![Fully paid order](assets/dashboard-orders/8.jpg)


#### Capture Payments

Unlike traditional transactions, capture payments are not instantly processed. You have 2 weeks to capture the payment manually, after which time it is automatically claimed. This is an advantage for retailers who do not want to pay transaction fees for refunds. Products can be shipped and confirmed by the customer before payment is processed. 

You can capture the full or partial amount (for example, taking only partial payment for an item due to damage, late delivery, or customer service issues) by clicking [[Capture]] in the bottom right corner and then confirming the full amount or changing the price to the new amount agreed with the customer.

![Order with captured payment](assets/dashboard-orders/9.jpg)


### Order History

Every time you complete an action such as confirming and fulfilling an order, a note appears in the order timeline at the bottom of the page. Administrators can add notes about interactions with clients and other information for other store workers.


## Creating an order

This is a function for store administrators to add orders, usually in cases where customer orders need to be resent but have already been fulfilled in the system. For example, if the customer was send damaged goods or is being sent a complimentary product due to customer service issues. It can also be used to create dummy and test orders and deal with stock issues.


### How to Create an Order

- Click [[Add Order]] on the main orders page and the draft orders section
- Select products from the drop-down menu or by typing the product name 
- Choose the customer name. Other customer information fields will then auto-complete.
- Choose the shipping from the drop-down list of available couriers

Once you set up the order and finalize it using the button in the footer, it becomes a normal order and replacement goods can be sent to the customer.


### Draft Orders

This is a list of orders created by administrators that have not yet been released to the system.