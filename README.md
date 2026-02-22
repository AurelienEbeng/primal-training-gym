# Functional Requirements
- Develop a pixel-perfect frontend implementation based on the provided [Figma design](https://www.figma.com/community/file/1498113978492175844/performance-driven-gym).
- Integrate the frontend with a backend system.
- Store user reservations in the database.
- Allow users to create, update, and delete their reservations.
- Implement full CRUD (Create, Read, Update, Delete) functionality for reservations.
- Prevent users from registering for classes scheduled in the past.
- Implement business logic within a service.py file instead of views.py.
- Display user reservations on a dedicated page in a tabular format.
- Implement the Create and Update reservation forms as modal dialogs.
- Dynamically update available class times in the form based on the selected class.
- Disable action buttons (create, update, delete) while a reservation request is being processed. Use useContext to manage button state globally.
- Redirect users to the reservation list page after successfully creating a reservation.
- Validate that users register for classes according to the correct time rules for weekdays, weekends, and holidays.
- Return descriptive error messages to the frontend when a reservation is invalid, including the specific reason.
- Deploy the frontend on Netlify and the backend on PythonAnywhere.
  <br>

# Technologies Used
## Frontend
- HTML
- CSS 
- React JS
- Tailwind CSS

## Backend
-Django

## Database
- SQLite
<br>

# [Live Website Link](https://primal-training-gym.netlify.app/)
