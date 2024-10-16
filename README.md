# Schedulrr

## Overview

Schedulrr is a full-stack meeting scheduling application built with Next.js, React, NeonDB, Prisma, Clerk, Google APIs, and Zod. The app allows users to effortlessly manage their meetings and availability with a user-friendly interface and a seamless booking experience.

## Features

- **User Authentication**: Integrated Clerk for secure and streamlined account creation and login, providing a hassle-free user authentication experience.
- **Personalized Dashboard**: Users are redirected to a customized dashboard with a unique link for booking public meetings, making it easy for others to schedule appointments.
- **Efficient Data Management**: NeonDB and Prisma are used for reliable event and user data storage, ensuring optimal performance and data integrity.
- **Automated Scheduling**: Automated calendar event creation and email invitations for scheduled meetings using Google APIs, improving convenience for both users and invitees.
- **Responsive Design**: Built with Tailwind CSS and Shadcn UI for a responsive and visually appealing interface, ensuring a great user experience across devices.
- **Input Validation**: Leveraged Zod for robust input validation, ensuring data integrity and preventing potential errors during scheduling.

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS, Shadcn UI
- **Backend**: Next.js API routes, Prisma, NeonDB
- **Authentication**: Clerk
- **Calendar Integration**: Google APIs
- **Validation**: Zod
- **Database**: NeonDB (PostgreSQL), Prisma ORM

## Usage

1. Sign up or log in using Clerk for a secure authentication process.
2. Once logged in, access your personalized dashboard with a unique link for public meeting bookings.
3. Manage your meetings, availability, and automatically create calendar events with Google APIs.
4. Receive email invitations for scheduled meetings.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
