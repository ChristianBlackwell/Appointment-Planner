**Contacts and Appointments Management App**

This project is a React application designed to manage contacts and appointments. It provides functionalities to add new contacts and appointments, display them, and ensure data integrity through duplication checks.

**Features**
Add new contacts with name, phone number, and email.
Add new appointments with title, contact, date, and time.
Display list of contacts and appointments.
Prevent duplicate contacts based on name.
Validate phone number format in contact form.
Use of controlled components for form inputs.
Use of React Router for navigation between Contacts and Appointments pages.

**Technologies Used**
React
React Router
HTML/CSS

**Usage**
**Add Contact:**
Navigate to the Contacts page.
Fill out the form with the contact's name, phone number, and email.
Click "Add Contact" to save the contact.

**Add Appointment:**
Navigate to the Appointments page.
Fill out the form with the appointment's title, select a contact, date, and time.
Click "Add Appointment" to save the appointment.

**View Contacts and Appointments:**
Both Contacts and Appointments are displayed on their respective pages.
Contacts are shown in a list with basic details.
Appointments are shown in a list with title, contact name, date, and time.
Components

**ContactsPage:**
Manages the state for contacts.
Renders the ContactForm for adding new contacts.
Displays the list of contacts using TileList.

**AppointmentsPage:**
Manages the state for appointments.
Renders the AppointmentForm for adding new appointments.
Displays the list of appointments using TileList.

**ContactForm:**
Renders a form for adding new contacts.
Uses controlled components for input fields.
Handles submission and form validation.

**AppointmentForm:**
Renders a form for adding new appointments.
Includes a ContactPicker component for selecting a contact.
Uses controlled components for input fields.
Handles submission and form validation.

**TileList:**
Receives an array of objects and renders Tile components for each object.
Used to display lists of contacts and appointments.

**Tile:**
Receives props (name and description) and renders a tile component.
Used by TileList to display individual contact or appointment details.

**Contact**
For any issues or questions, please feel free to reach out to me.
