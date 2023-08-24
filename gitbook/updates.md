# Updates

{% hint style="info" %}
**If you don't see the update in Dashboard, refresh the page with a cache cleanup. For Windows: "Ctrl + Shift + R", for Mac: "Cmd + Shift + R" (the combination may be different, depending on your browser).**
{% endhint %}

### August 24, 2023

1. A [Microscopy section](en/menu/patient-record-section/microscopy.md) has been added to the patient's profile. The section consists of two parts: image uploading is possible only from the doctor's profile, while filling out the questionnaire is feasible from both the doctor's and the patient's profiles.
2. The [doctor's](en/menu/doctors-schedule.md) and [patient's schedules](en/menu/patient-record-section/schedule.md) (both in the dashboard and personal profile) now display comments. The data is fetched from the Simplybook system.
3. Preparation for inventory management improvement has been carried out: a date input field has been added when adding an inventory item or changing the quantity of an item in the inventory.
4. In the Treatments List addition section, information about the time already spent by other lists within the selected period has been incorporated.

### August 16, 2023

1. Two rooms were hidden from the Online Booking system: Dorado King, Coral Room - at the moment they are available for booking only from Dashboard. Cabo Room was hidden from all systems earlier.
2. Added restriction on editing bookings: if there are less than 21 days left before the check-in date, only users with a certain access level can edit it.
3. In the Online Booking system, the weekday of check-in has been changed to Saturday.

### August 9, 2023

1. [Create/Edit Bookings](en/menu/booking-section/creating-a-new-booking.md): The minimum prepayment threshold is $400. Threshold does not work for "non-clients".
2. [Treatments List](en/menu/patient-record-section/list-of-procedures.md#creating-a-list-of-procedures): a field has been added to select the period for which the list is drawn up. You can add a list for the current week, for the next week, or for an arbitrary period. The field is required.
3. [Treatments List](en/menu/patient-record-section/list-of-procedures.md#creating-a-list-of-procedures): added display of time available for procedures. Look [here](en/menu/patient-record-section/list-of-procedures.md#creating-a-list-of-procedures).

### August 2, 2023

Fixed a bug on the invoice creation/editing page that occurred when searching for treatments.

### July 26, 2023

1. Additional ways to filter tasks have been added to the [ToDo section](en/menu/to-do-section/user-tasks.md).&#x20;
2. Fixed minor display errors in invoice categories.&#x20;
3. Unused procedures have been hidden in the Invoices and in the Treatments Lists.&#x20;
4. The procedures table in the database has been completely updated.&#x20;
5. Preparations for the implementation of functionality for adding procedures to the shopping cart on the site.

### July 12, 2023

1. Added [Stock section](en/menu/stock/).&#x20;
2. Adjusted the Expenses section.&#x20;
3. Updated database structure

### July 2, 2023

1. Added the ability to add gratuity to [invoices](en/menu/invoices-section/creating-new-invoice.md) when creating and editing.
2. Updated appearance of invoices.
3. Optimized the method of constructing invoices.
4. Prepared for adding the "Stock" section: navigation and placement of the section on the site.

### June 28, 2023

1. Therapists have been added the ability to mark performed procedures in [the schedule](en/menu/doctors-schedule.md).
2. Corrected errors with time in [the ToDo section](en/menu/to-do-section/creating-tasks.md).&#x20;
3. Preparations have been made to create the Warehouse section:
   1. Structured data.
   2. Made changes to the Expenses section.
4. Corrected the display of the schedule in the patient's personal account.
5. Fixed sorting of invoices when requesting more than 50 items.

### June 22, 2023

Dashboard:

1. Calendar view: added columns with information about who and from which system the order was created.
2. Calendar View: added filtering of the list by customer status - current customer or new customer.
3. Creating a booking: now when creating an order you can specify one of the three client statuses - "patient", "accompaining person", "not client".

Client application:

1. Added mandatory confirmation of Patient Agreement when logging in for the first time.
2. Orders presentation has been changed, displayed data have been enlarged.

General:

1. Added additional user email verification.
2. Optimized request processing speed.
3. Improved Dashboard interface.

### June 11, 2023

A package of procedures has been added to the application. The package is selected when [creating/editing a booking](en/menu/booking-section/creating-a-new-booking.md) from the Dashboard.

### June 9, 2023

The error of time recording when creating the Treatments List and the Tests List (Analyses) was corrected: when viewing the history of these lists, the time zone is added.&#x20;

Recall that the time for which you want to assign a treatments list or test list, you can set manually (both in the past and in the future time), and the default setting is the current time in the time zone, which is selected on the PC.

### June 6, 2023

1. [Physicians schedule](en/menu/doctors-schedule.md) was added to Dashboard (new item in the main menu — "Schedule").
2. On the [page of bookings](en/menu/booking-section/viewing-all-bookings.md): when sending emails to clients, for the emails of the category "After deposit info" the choice of the letter language has been added (Russian and English).
3. Added restriction of [procedure list creation](en/menu/patient-record-section/list-of-procedures.md#creating-a-list-of-procedures): amount of days chosen for a procedure may not exceed the amount of procedures. The number of procedures has a higher priority than the number of selected days.
