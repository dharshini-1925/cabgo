# CABGO – Cab Booking Application

## Software Requirements Specification (SRS)

### 1. Introduction

**Project Name:** CABGO – Cab Booking Application

**Purpose:** CABGO is a cab booking application designed to help users book rides easily, select cab types, view estimated fares, and manage their bookings through a user-friendly interface.

**Scope:** The application includes user registration, login, cab booking, ride details, payment options, and booking history. The project will be developed in two sprints.

### 2. Functional Requirements

Functional requirements describe what the application must do.

**FR1 – User Registration**

* The system shall allow new users to register using their name, email, mobile number, and password.
* The system shall validate the required registration fields.

**FR2 – User Login**

* The system shall allow registered users to log in.
* The system shall validate login credentials.
* The system shall provide a forgot-password option in the interface.

**FR3 – Pickup and Drop Locations**

* The system shall allow users to enter pickup and destination locations.
* The system shall check that both locations are provided before booking.

**FR4 – Cab Selection**

* The system shall provide Mini, Sedan, and SUV cab options.
* The system shall display the selected cab type.

**FR5 – Fare Estimation**

* The system shall display an estimated fare based on the selected cab and trip details.
* The final fare may vary depending on distance and applicable charges.

**FR6 – Cab Booking**

* The system shall allow users to submit a cab booking request.
* The system shall generate a booking reference when a booking is successfully created.

**FR7 – Booking Confirmation**

* The system shall display booking confirmation and booking details.

**FR8 – Driver and Ride Details**

* The system shall display assigned driver details when available.
* The system shall display the ride status.

**FR9 – Booking History**

* The system shall allow users to view their previous bookings.

**FR10 – Booking Cancellation**

* The system shall allow users to cancel eligible bookings.
* The system shall update the booking status after cancellation.

**FR11 – Payment**

* The system shall display available payment methods.
* The system shall show payment status when payment functionality is implemented.

### 3. Non-Functional Requirements

Non-functional requirements describe how the application should perform.

**NFR1 – Usability:** The interface shall be simple, attractive, and easy to navigate.

**NFR2 – Performance:** Pages and booking actions should respond within a reasonable time under normal operating conditions.

**NFR3 – Security:** Passwords must be stored securely if authentication is implemented. User information must be protected from unauthorized access.

**NFR4 – Reliability:** The system should handle errors and invalid inputs without crashing.

**NFR5 – Compatibility:** The application should support commonly used modern web browsers and suitable screen sizes.

**NFR6 – Maintainability:** The code and project documentation should be organized for easy updates.

**NFR7 – Availability:** The deployed application should be available to users whenever its hosting service is operational.

### 4. Hardware Requirements

* Computer or laptop for development.
* Minimum 4 GB RAM recommended.
* Keyboard, mouse, and internet connection.
* Smartphone or computer for application testing.

### 5. Software Requirements

* Operating System: Windows, Linux, or macOS.
* Browser: Google Chrome, Microsoft Edge, or Firefox.
* Wireframe Tool: diagrams.net (draw.io).
* Version Control: Git.
* Repository Hosting: GitHub.
* Development Tools: Visual Studio Code or another code editor.
* Frontend: HTML and CSS; JavaScript if interactive features are required.
* Backend and database: To be selected if account authentication, bookings, and persistent storage are implemented.

### 6. User Requirements

**Customer:**

* Register and log in.
* Enter pickup and destination locations.
* Select a cab and view the estimated fare.
* Book a ride and view booking details.
* View booking history and cancel eligible bookings.

**Administrator (future enhancement):**

* Manage user accounts and booking records.
* Monitor bookings and booking status.
* Manage cab and driver information.

### 7. Development Plan

**Sprint 1 – Login and Cab Booking**

* Design login and registration pages.
* Add pickup and drop location fields.
* Add cab selection.
* Display estimated fare.
* Implement the booking request interface.

**Sprint 2 – Booking Management**

* Add booking confirmation.
* Display driver and ride details.
* Add booking history.
* Implement booking cancellation.
* Add payment interface and test the application.

### 8. Assumptions and Constraints

* Users have access to a computer or smartphone and an internet connection.
* Real-time tracking requires location services and a suitable mapping service.
* Online payments require integration with a payment provider.
* Actual login, booking, and history features require application logic and data storage; a wireframe alone does not implement these features.

### 9. Conclusion

CABGO aims to provide a convenient and user-friendly cab booking experience. These requirements guide the design, development, testing, and future enhancement of the application.
