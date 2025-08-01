# Job Search App

## 📌 Overview
The **Job Search App** is designed to help users find job opportunities relevant to their domain or area of interest. It provides a structured and efficient job search experience by allowing users to filter jobs, manage applications, and interact with company listings. The application's architecture is modular, with different components created under `index.js`, which serves as the root file. These components handle API calls, job posting details, and error management for incorrect entries.

## 🚀 Features
- 🔍 **Job Filtering** – Apply filters to find relevant job listings.
- 👤 **User Management** – Handles user data, including account creation and login.
- 🏢 **Company Management** – Companies can post job listings and manage applicants.
- 📄 **Job Applications** – Users can apply for jobs and track application status.
- ⚠️ **Error Handling** – Displays meaningful error messages for incorrect inputs.

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Scheduler:** CRON Jobs for OTP expiration cleanup

## 📄 Project Structure
```
├── index.js            # Root file
├── models             # Database models
├── routes             # API routes
├── controllers        # Business logic
├── middleware         # Authentication & error handling
└── utils              # Helper functions (OTP, email service)
```
- 📨 API Documentation: [Postman Collection](https://documenter.getpostman.com/view/39725396/2sAYdoFnmP)
