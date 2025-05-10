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

