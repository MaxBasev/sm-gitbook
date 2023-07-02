---
layout: landing
---

# Creating a new booking

To create a new booking, you need to click on the "Booking" ➡️ "Create New" link in the main menu, as shown in the image:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-05-26 at 16.03.42 (1).png" alt=""><figcaption></figcaption></figure>

After that, a window will open with only one field for entering the check-in date. Clicking on the field will display a special date selection form:

<figure><img src="../../../.gitbook/assets/image (3) (2) (1).png" alt=""><figcaption></figcaption></figure>

After selecting the date, a button for adding a client will appear:

<figure><img src="../../../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

Upon clicking the "Add Client" button, a data entry form for the guest within the booking will appear, and the "Add Client" button will move below the form. Each click on the button will display a new form, allowing you to add the required number of clients to the booking.

The data entry form for the guest looks as follows:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-06-22 at 17.14.43.png" alt=""><figcaption></figcaption></figure>

1 — Serial number of the guest in the order.

2 — Remove the guest from the booking.&#x20;

3 — Client type: new client or client already existing in the system.&#x20;

4 — Input fields for the new client's data (all fields are mandatory).&#x20;

5 — Client status in the booking.

{% hint style="info" %}
**Please note!**

The system has еркуу client statuses.

1. Patient: a client who comes to the clinic for procedures.
2. Accompanying person: a client who does not undergo any procedures but stays in one of the clinic's rooms. For such clients, there is an additional "Meal" field, which is paid separately.
3. NOT CLIENT.

When creating a booking through the Bookings system, only two statuses are available — patient and accompanying person. Only one accompanying person is available per patient.
{% endhint %}

6 — Room where the client will stay.

{% hint style="info" %}
**Please note!**

The Dashboard system has a special room/location called "Visiting", which should be used for incoming clients who do not need to stay in the clinic's rooms.
{% endhint %}

7 — he field for selecting a package of procedures.

8 — Comment visible to the client in their personal account.&#x20;

9 — Comment visible only to Dashboard users.

10 — Button "Add a patient to the order"

If the client already exists in the system, the client selection field will look as follows:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-05-26 at 16.15.02.png" alt=""><figcaption></figcaption></figure>

In the image: a client search field and a dropdown list of all system clients. To select a user, it is not enough to simply enter their data; you need to click on the client in the dropdown list.

If the client being added to the booking is not a future patient, the data will look as follows:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-05-26 at 16.16.15.png" alt=""><figcaption></figcaption></figure>

In the image, you can see that the client's status has changed to "Companion," and a field for adding meal payment to the booking has appeared.

At the bottom of the page, after adding clients to the booking, the following data is specified:

<figure><img src="../../../.gitbook/assets/Screenshot 2023-05-26 at 16.49.41.png" alt=""><figcaption></figcaption></figure>

1 — Number of days of stay in the clinic, and 2 — Check-out date. These two fields are linked, so you can change either one, and the other will be automatically calculated. By default, when creating a new booking, the stay duration in the clinic is set to 7 days and 6 nights.

3 — Total price of the booking. This field is calculated automatically and cannot be manually changed.

4 — Prepayment input field.

5 — Create Booking button.

If the prepayment field is not filled in, after saving the booking, it will have the status "Awaiting Confirmation" and will expire after one hour from the booking creation time if not confirmed.

After creating the booking, the page for editing the booking will open.
