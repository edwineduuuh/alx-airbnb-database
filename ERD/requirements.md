# ERD Requirements

## Entities
- User
- Property
- Booking
- Review

## Attributes
- User: user_id, name, email, etc.
- Property: property_id, owner_id, location, price
- Booking: booking_id, user_id, property_id, start_date, end_date
- Review: review_id, booking_id, user_id, rating, comment

## Relationships
- A User **makes** Bookings
- A Booking **includes** one Property
- A Booking **has** one Review (optional)
- A User **writes** a Review

![er-diagram-airbnb-alx](https://github.com/user-attachments/assets/15ad1f47-b0f7-4132-ae10-ad517e9c9d27)
