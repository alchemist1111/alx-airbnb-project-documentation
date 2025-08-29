# Airbnb Clone Backend User Stories

This document contains the user stories for the Airbnb Clone project, derived from the system's use case diagram. These user stories outline the key interactions between users and the system.

## User Stories

### 1. User Registration and Login
- **Story**: 
  - *As a guest or host, I want to register an account so that I can access the platform and manage my activities, such as searching for properties or listing them.*
- **Acceptance Criteria**:
  - User can register via email or third-party OAuth (Google/Facebook).
  - User is able to access the platform after successful registration.

### 2. Property Listing by Host
- **Story**:
  - *As a host, I want to be able to list a property on the platform so that I can rent it out to guests.*
- **Acceptance Criteria**:
  - Host can add details such as the title, description, location, price, amenities, and availability of the property.
  - Property is successfully listed after submission.

### 3. Search and Book Property by Guest
- **Story**:
  - *As a guest, I want to search for properties based on various criteria (location, price, amenities) so that I can find the best place to stay for my trip.*
- **Acceptance Criteria**:
  - Guest can filter properties by location, price, number of guests, and amenities.
  - Guest can view detailed property information and make a booking.

### 4. Payment for Booking
- **Story**:
  - *As a guest, I want to make a secure payment for my booking so that I can confirm my reservation and the host can receive payment.*
- **Acceptance Criteria**:
  - Guest can enter payment information and complete the payment through a secure payment gateway (e.g., Stripe, PayPal).
  - Payment is processed, and the guest and host receive a confirmation.

### 5. Review and Rating
- **Story**:
  - *As a guest, I want to leave a review and a rating for a property after my stay so that I can share my experience with other users.*
- **Acceptance Criteria**:
  - Guest can leave a review and rating after the booking is completed.
  - Host can respond to the review.
