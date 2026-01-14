# Healthcare Management System

A personal project - Healthcare patient management application built with Next.js.

## Tech Stack

- Next.js
- Appwrite
- TypeScript
- TailwindCSS
- ShadCN
- Twilio

## Features

- **Patient Registration**: Users can sign up and create a personal profile as a patient
- **Appointment Booking**: Patients can schedule appointments with doctors
- **Admin Dashboard**: Administrators can view and manage all scheduled appointments
- **Appointment Management**: Admins can confirm, schedule, or cancel appointments
- **SMS Notifications**: Patients receive SMS notifications for appointment confirmations
- **Responsive Design**: Works seamlessly on all device types and screen sizes
- **File Upload**: Secure file upload using Appwrite storage
- **Performance Monitoring**: Application monitoring using Sentry

## Quick Start

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials from [Appwrite](https://appwrite.io/).

### Run the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.