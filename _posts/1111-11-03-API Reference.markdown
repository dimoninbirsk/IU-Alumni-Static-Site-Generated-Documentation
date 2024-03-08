---
layout: post
title:  "API Reference"
tag: API
permalink: api
---
## User Authentication API
This API provides endpoints for user authentication, registration, and account management.

### Endpoints
- Login (POST /login): Authenticate a user using email and password.
- Register (POST /register): Create a new user account.
- Register Admin (POST /register-admin): Create a new admin user account.
- Update Account (POST /update): Update the current user's account information.
- Update Password (POST /update-password): Update the current user's password.
- Get Current User (GET /): Retrieve the current user's information.
- Get All Users (GET /all): Retrieve information about all registered users.
- Forgot Password (POST /forgot-password): Send a password reset email to the user's university email address.
- Update Password (POST /forgot-update-password): Update the user's password after they have forgotten it.
- Verify Account (POST /verify-account): Send a verification email to the user's university email address.
- Confirm Verification (POST /confirm_verification): Verify the user's account using the code sent to their email.
- SSO Login (GET /login_sso): Redirect to the SSO login page.
- SSO Callback (GET /callback): Handle the SSO callback and authenticate the user.

---

## Obtain Pass API
This API provides endpoints for managing pass requests.

### Endpoints
- Get All Pass Requests (GET /): Retrieve all pass requests made by the current user.
- Get All Pass Requests (GET /admin): Retrieve all pass requests (for admins only).
- Update Pass Request (PATCH /): Update a pass request.
- Create Pass Request (POST /): Create a new pass request.
- Delete Pass Request (DELETE /): Delete a pass request.

---

## Elective Courses API
This API provides endpoints for managing elective courses and course requests.

### Endpoints
- Get All Elective Courses (GET /): Retrieve all elective courses.
- Get All Elective Courses (GET /admin): Retrieve all elective courses (for admins only).
- Get Booked Elective Courses (GET /booked): Retrieve all elective courses booked by the current user.
- Get All Elective Requests (GET /request): Retrieve all elective course requests (for admins only).
- Create Elective Course (POST /): Create a new elective course.
- Create Elective Courses in Bulk (POST /bulk): Create multiple elective courses at once.
- Update Elective Course (PUT /): Update an existing elective course.
- Delete Elective Course (DELETE /remove): Delete an elective course.
- Disconnect Elective Course Request (DELETE /): Disconnect an elective course request from the current user.
- Request Elective Course (POST /request): Request to enroll in an elective course.
- Update Elective Request (PATCH /): Update an elective course request.

---

## Manage Donations API
This API provides endpoints for managing donations.

### Endpoints
- Get All Donations (GET /): Retrieve all donations made by alumni.
- Make Donation (POST /): Make a donation.
- Get Admin Donation Message (GET /admin): Retrieve the admin's donation message.
- Update Admin Donation Message (POST /admin): Update the admin's donation message.