# CarePulse - Healthcare Patient Management System

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Future Improvements](#future-improvements)
5. [Quick Start](#quick-start)

## 🤖 Introduction
CarePulse is a healthcare patient management application designed to streamline the process of patient registration, appointment scheduling, and management. It enables patients to easily register, book appointments, and manage their interactions with healthcare providers. The app also provides administrative tools for scheduling, confirming, and canceling appointments, with real-time SMS notifications for patient engagement. Built with cutting-edge technologies like Next.js and Twilio, it ensures secure, scalable, and responsive performance across all devices.

## ⚙️ Tech Stack
- **Next.js** - Framework for server-side rendering and building web applications.
- **Appwrite** - Backend platform providing secure authentication and storage.
- **TypeScript** - Strongly-typed language for building robust, error-free code.
- **TailwindCSS** - Utility-first CSS framework for fast and responsive UI design.
- **ShadCN** - Component library for maintaining a clean and consistent UI.
- **Twilio** - API for sending SMS notifications to patients.
- **Sentry** - Application performance monitoring and error detection.

## 🔋 Features

### 👉 Register as a Patient
Patients can sign up and create personal profiles securely through the registration system.

### 👉 Book a New Appointment with Doctor
Patients can schedule appointments with healthcare providers at their convenience, with the option to book multiple appointments.

### 👉 Manage Appointments on Admin Side
Administrators have full access to view and manage all scheduled appointments within the system.

### 👉 Confirm/Schedule Appointments from Admin Side
Admins can confirm appointment bookings and set time slots to ensure proper scheduling.

### 👉 Cancel Appointments from Admin Side
Administrators can cancel appointments with ease as per the system's requirements.

### 👉 Send SMS on Appointment Confirmation
Patients receive real-time SMS notifications confirming the details of their booked appointments via Twilio.

### 👉 Complete Responsiveness
The application is fully responsive, delivering a seamless experience across all devices including desktops, tablets, and smartphones.

### 👉 File Upload Using Appwrite Storage
Patients and admins can upload and securely store necessary documents using Appwrite's storage services.

### 👉 Manage and Track Application Performance Using Sentry
Sentry is integrated to monitor performance and detect errors, ensuring the application runs smoothly and securely.


## 🛠️ Future Improvements

Here are some potential future enhancements to improve functionality and user experience:

1. **Integration with Payment Gateways**  
   Allow patients to make secure online payments for consultations and treatments directly through the platform.

2. **Calendar View for Appointment Management**  
   Implement a calendar view for both patients and administrators to easily visualize and manage upcoming appointments.

3. **Automated Appointment Reminders**  
   Send automated SMS/email reminders to patients for their upcoming appointments to reduce no-shows.

4. **Patient Medical History and Reports**  
   Allow patients to upload, store, and manage their medical records and history for easy access during future consultations.

5. **Doctor and Patient Ratings & Reviews**  
   Implement a rating and review system for patients to provide feedback on their doctors, enhancing trust and service quality.

6. **Multi-language Support**  
   Provide the option for patients and administrators to use the platform in multiple languages for better accessibility.

7. **Telemedicine/Video Consultations**  
   Introduce a video conferencing feature to allow remote consultations between doctors and patients.

8. **Enhanced Analytics Dashboard**  
   Create a detailed analytics dashboard for administrators to track appointment trends, patient demographics, and other useful metrics.

9. **Role-based Access Control (RBAC)**  
   Implement advanced user roles and permissions for better security and data access control, differentiating between doctors, patients, and administrators.

10. **Integration with External Health APIs**  
    Connect the platform to external health data providers to allow real-time syncing of patient health metrics (e.g., wearables data).


## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- **Git**
- **Node.js**
- **npm** (Node Package Manager)

### Cloning the Repository

To clone the repository, run the following command:

```bash
git clone https://github.com/Rohit61181/healthcare.git
cd healthcare
```

### Installation

Install the project dependencies using npm:

```bash
npm install
```

### Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

```plaintext
# APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=123456
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite](#Appwrite)

### Running the Project

To run the project, use the following command:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
