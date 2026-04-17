# booking-system
Questions and answer
**1. easiest part**
The easiest part was creating the classes (User, Resource, Booking) and adding their basic attributes because it was straightforward.
**2. hardest part**
The hardest part was handling the booking rules, especially making sure a resource cannot be double-booked and updating it correctly after cancellation.
**a bug and how i fixed it**
One bug I faced was that the resource was not becoming available after cancelling a booking. I fixed it by making sure the clear_booking method was called when the booking status changed to cancelled
