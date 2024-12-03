# Hospital Management System

The **Hospital Management System** is a comprehensive web application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a user-friendly platform for managing hospital services, doctor appointments, medicine e-commerce, and location-based hospital suggestions.  

## Features  

### 1. **Authentication**  
- Complete login and signup functionality.  
- Role-based access for users, doctors, and admins.  

### 2. **Location Tracker**  
- Tracks the user’s exact location.  
- Displays the nearest best hospitals within a 5 km radius.  

### 3. **E-Commerce Functionality**  
- Includes a cart for specific medicines only.  
- Advanced filter options for searching medicines.  

### 4. **Blogs Section**  
- Blogs written by authenticated doctors.  
- Blogs are accessible to all users for health-related insights.  

### 5. **Appointment Management**  
- Users can:  
  - Select a doctor and department.  
  - Choose a time slot for the appointment.  
  - Send the appointment request to the doctor.  
- Doctors can:  
  - Accept or reject appointment requests.  
  - Manage their appointment schedules.  

### 6. **Admin Panel**  
- Accessible by authenticated admins.  
- Admins can:  
  - Manage users, doctors, and hospital data.  
  - Oversee e-commerce activities.  
  - Handle doctor authentication and schedule management.  

## Technology Stack  

### Frontend  
- **React.js**: For building a responsive and dynamic user interface.  
- **React Router**: For seamless navigation between pages.  

### Backend  
- **Node.js**: Server-side environment for handling API requests.  
- **Express.js**: Framework for building RESTful APIs.  

### Database  
- **MongoDB**: NoSQL database for storing application data.  

### Additional Tools  
- **Google Maps API**: For location tracking and displaying nearby hospitals.  
- **JWT (JSON Web Tokens)**: For secure authentication and session management.  

## Installation and Setup  

### Prerequisites  
- Node.js installed on your system.  
- MongoDB instance (local or cloud-based like MongoDB Atlas).  

### Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/hospital-management-system.git
   cd hospital-management-system
