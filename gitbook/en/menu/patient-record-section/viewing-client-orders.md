---
layout: landing
---

# Viewing client's orders.

The first menu item on the client's page is their orders. In the top right corner, there is a button to refresh the user's order data (1). Below, there is a list of all the user's orders displayed as cards.

<figure><img src="../../../.gitbook/assets/Screenshot 2023-05-24 at 20.15.40.png" alt=""><figcaption></figcaption></figure>

The order card (2) consists of the following elements (as shown in the image):

3 - Booking dates.

4 - Order status. The following options are possible:

* Awaiting confirmation (order has been placed but payment has not been made yet).
* Expired (order was placed, but payment was not made within an hour). Such an order can be changed to confirmed by editing the order and providing payment information (if the room specified in the order is already booked, it will need to be changed during editing).
* Future (confirmed order that is yet to come).
* Current (confirmed order, client is currently in the clinic).
* Past (confirmed order that has already ended).
* Canceled - Orders can only be canceled manually in the Dashboard, and canceled orders cannot be restored.

5 - Order creation information: when the order was created and in which system (Dashboard or Booking page).

6 - Overall payment information for the order (base cost of the order, amount of prepayment made, whether the order is fully paid).

7 - List of patients in the order.

8 - Quick order editing buttons:

* Order confirmation button: When clicked, a form appears with a field to enter the prepayment amount (button only available for orders awaiting confirmation).
* Order cancellation button: When clicked, a confirmation window appears before proceeding with the cancellation operation. After confirmation, the order status changes to Canceled.
* Full payment button: When clicked, a confirmation window appears for the operation (button unavailable for canceled and expired orders).

9 - [Order editing](../booking-section/edit-booking.md) button.

10 - Order history.
