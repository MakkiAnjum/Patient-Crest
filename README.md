![patient-crest-1](https://github.com/user-attachments/assets/28560bd6-7a94-4530-82df-d4c873890535)# Patient Crest

## Healthcare Appointment Management System

This project is a healthcare appointment management system built using cutting-edge technologies to provide a seamless experience for patients and administrators. It leverages **Next.js** for the frontend, **Appwrite** for backend services, **TypeScript** for static typing, **TailwindCSS** and **ShadCN** for styling, and **Twilio** for SMS notifications.

![patient-crest-1](https://github.com/user-attachments/assets/d4961617-aa05-4ec2-a6fb-1b8499e6b0cb)


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Features

- **Register as a Patient**: Users can sign up and create a personal profile as a patient.
- **Book a New Appointment with Doctor**: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.
- **Manage Appointments on Admin Side**: Administrators can efficiently view and handle all scheduled appointments.
- **Confirm/Schedule Appointment from Admin Side**: Admins can confirm and set appointment times to ensure they are properly scheduled.
- **Cancel Appointment from Admin Side**: Administrators have the ability to cancel any appointment as needed.
- **Send SMS on Appointment Confirmation**: Patients receive SMS notifications to confirm their appointment details.
- **Complete Responsiveness**: The application works seamlessly on all device types and screen sizes.
- **File Upload Using Appwrite Storage**: Users can upload and store files securely within the app using Appwrite storage services.
- **Manage and Track Application Performance Using Sentry**: The application uses Sentry to monitor and track its performance and detect any errors.
- **Code Architecture and Reusability**: Designed with modular architecture for code reusability and maintainability.

## Technologies Used

- **Next.js**: A React framework for building fast and user-friendly web applications.
- **Appwrite**: An open-source backend server providing authentication, database, and storage services.
- **TypeScript**: A superset of JavaScript that adds static typing for improved code quality.
- **TailwindCSS**: A utility-first CSS framework for creating responsive designs.
- **ShadCN**: A component library for building modern UIs.
- **Twilio**: A cloud communications platform for sending SMS notifications.
- **Sentry**: A real-time application monitoring tool for detecting errors and performance issues.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/makkianjum/patient-crest.git
   cd patient-crest
   ```

2. **Install dependencies:**

   Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine. Then, run:

   ```bash
   npm install
   ```

3. **Set up Appwrite:**

   Follow the [Appwrite documentation](https://appwrite.io/docs) to set up your Appwrite server. Ensure you have your project and database configured.

4. **Set up Sentry:**

   Register your project with [Sentry](https://sentry.io/) and obtain your DSN.

5. **Configure Twilio:**

   Sign up for a Twilio account and set up your SMS service. Obtain your account SID, auth token, and phone number.

## Configuration

Create a `.env.local` file in the root directory and add the following environment variables:

```plaintext
NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
NEXT_PUBLIC_APPWRITE_PROJECT=<your-appwrite-project-id>
TWILIO_ACCOUNT_SID=<your-twilio-account-sid>
TWILIO_AUTH_TOKEN=<your-twilio-auth-token>
TWILIO_PHONE_NUMBER=<your-twilio-phone-number>
SENTRY_DSN=<your-sentry-dsn>
```

## Usage

To start the development server, run:

```bash
npm run dev
```

This will launch the application at `http://localhost:3000`.

### Building for Production

To build the application for production, run:

```bash
npm run build
```

This will generate optimized static files in the `out` directory.

### Running Tests

To run tests, use:

```bash
npm test
```
