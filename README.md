# ShareSpace

A dynamic social media platform that enables users to share thoughts, connect with others, and engage in discussions seamlessly. Built using modern web technologies for a smooth and intuitive user experience.

## Overview

- **Project Name**: ShareSpace
- **Category**: Social Media Platform
- **Tech Stack**: Next.js, Tailwind CSS, PostgreSQL, Prisma, Clerk, Railway, Cloudinary, Vercel
- **Live Demo**: [ShareSpace](https://share-spcae.vercel.app/)

## Features

- **User Authentication**: Secure sign-up and login functionalities powered by Clerk.
- **Post Creation**: Create, edit, and delete posts with rich text and media support.
- **Image Hosting**: Integrated with Cloudinary for efficient image storage and retrieval.
- **Database Management**: Uses PostgreSQL and Prisma ORM for seamless data handling.
- **Deployment**: Hosted on Vercel with backend services managed by Railway.
- **Responsive UI**: Fully optimized for desktops, tablets, and mobile devices.

## Installation & Setup

To run the project locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Nikhiljai03/ShareSpcae.git
   cd ShareSpcae
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:

   Create a `.env` file in the root directory and add necessary environment variables.

4. **Run Database Migrations**:

   ```bash
   npx prisma migrate dev
   ```

5. **Start the Development Server**:

   ```bash
   npm run dev
   ```

   The application will be available at [http://localhost:3000](http://localhost:3000).

## Contribution Guide

Contributions are welcome! Follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make your changes and commit**:
   ```bash
   git commit -m 'Add some feature'
   ```
4. **Push to your branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Create a pull request** and describe your changes.

## Requirements

- Node.js 16+
- PostgreSQL
- Prisma ORM
- Cloudinary Account (for image uploads)

---

Happy Coding! 🚀
