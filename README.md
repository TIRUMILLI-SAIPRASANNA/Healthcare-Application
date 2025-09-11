<div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
</div>

<h3 align="center">A HealthCare Management System</h3>

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets (Code to Copy)](#snippets)
6. 🔗 [Assets](#assets)

## 🤖 Introduction

A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.

## ⚙️ Tech Stack

- Next.js
- Appwrite
- TypeScript
- TailwindCSS
- ShadCN
- Twilio

## 🔋 Features

- **Register as a Patient**
- **Book a New Appointment with Doctor**
- **Manage Appointments on Admin Side**
- **Confirm/Schedule Appointment from Admin Side**
- **Cancel Appointment from Admin Side**
- **Send SMS on Appointment Confirmation**
- **Complete Responsiveness**
- **File Upload Using Appwrite Storage**
- **Manage and Track Application Performance Using Sentry**

…and more, including code architecture and reusability.

## 🤸 Quick Start

**Prerequisites**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/TIRUMILLI-SAIPRASANNA/Healthcare-Application.git
cd healthcare
Install Dependencies
npm install
Set Up Environment Variables
Create a .env.local file in the root:
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=984930

Replace placeholders with your Appwrite credentials.

Running the Project
npm run dev
Visit http://localhost:3000
🕸️ Snippets

Your key config and type files (tailwind.config.ts, app/globals.css, types/index.d.ts, etc.) can go here or in a docs/snippets folder.
🔗 Assets

Public assets used in the project can be found here

