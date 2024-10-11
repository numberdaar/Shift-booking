# Shift Management Application

This Shift Management Application is a web-based tool for managing and viewing shifts. The app provides two main views: "My Shifts" for booked shifts and "Available Shifts" for unbooked shifts. Users can navigate between these views, book new shifts, and cancel existing ones. The app is built with React, Redux, and Tailwind CSS, and it leverages Redux for state management to handle booked shifts.

## Features

- **Tab Navigation**: Switch between "My Shifts" and "Available Shifts" views.
- **Shift Booking and Cancellation**: Book and cancel shifts with real-time updates.
- **Date Grouping**: Shifts are grouped by date for easy navigation.
- **State Persistence**: Booked shifts are saved in `localStorage` to persist data across sessions.
- **Responsive Design**: The app is responsive and works on various screen sizes.

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/shift-management-app.git
   cd shift-management-app
   npm Install 
   npm start

## Backend
In a separate terminal window, clone the backend repository:

```bash
   git clone https://github.com/numberdaar/Shift-booking-backend-api.git
   cd Shift-booking-backend-api
   npm Install 
   npm start  
   ```

## Keep in mind 
   API server runs at localhost:8080