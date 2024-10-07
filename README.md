
# StudyNotion - EdTech Platform

## Introduction

**StudyNotion** aims to provide a seamless and interactive learning experience for students, making education more accessible and engaging. Additionally, the platform serves as a venue for instructors to showcase their expertise and connect with learners across the globe.

In the following sections, we will cover the technical details of the platform.

## System Architecture

The StudyNotion EdTech platform consists of three main components: the front-end, the back-end, and the database. The platform follows a client-server architecture, with the front-end serving as the client and the back-end and database serving as the server.

### Front-end

The front-end of the platform is built using **ReactJS**, allowing for the creation of dynamic and responsive user interfaces, crucial for providing an engaging learning experience. The front-end communicates with the back-end using RESTful API calls.

#### Front End Pages

**For Students:**
- **Homepage:** A brief introduction to the platform with links to the course list and user details.
- **Course List:** Displays all the available courses along with descriptions and ratings.
- **Wishlist:** Shows all courses added to the student's wishlist.
- **Cart Checkout:** Enables users to complete course purchases.
- **Course Content:** Presents the content for each course, including videos and related materials.
- **User Details:** Displays account details, including name, email, and other relevant information.
- **User Edit Details:** Allows students to update their account information.

**For Instructors:**
- **Dashboard:** Provides an overview of the instructor's courses, ratings, and feedback.
- **Insights:** Offers detailed metrics, including views, clicks, and other relevant statistics.
- **Course Management Pages:** Enables instructors to create, update, and delete courses, manage content, and set pricing.
- **View and Edit Profile Details:** Allows instructors to manage their account information.

#### Front-end Tools and Libraries

The front-end utilizes various frameworks and libraries, including:
- **ReactJS**
- **CSS** and **Tailwind** for styling
- **Redux** for state management

### Back-end

The back-end of the platform is built using **NodeJS** and **ExpressJS**, providing APIs for the front-end to consume. These APIs handle functionalities such as user authentication, course creation, and consumption. The back-end also processes and stores course content and user data.

#### Back-end Features

- **User Authentication and Authorization:** Secure sign-up and log-in using email addresses and passwords, along with OTP verification and password recovery.
- **Course Management:** Instructors can create, read, update, and delete courses while students can view and rate them.
- **Payment Integration:** Allows students to purchase and enroll in courses through Razorpay for secure payment handling.
- **Cloud-based Media Management:** Utilizes **Cloudinary** for storing and managing media content (images, videos, documents).
- **Markdown Formatting:** Course content is stored in Markdown format for easier display and rendering.

#### Back-end Frameworks, Libraries, and Tools

The back-end employs a variety of technologies, including:
- **Node.js** for server-side development
- **Express.js** for building web applications
- **MongoDB** for flexible and scalable data storage
- **JWT (JSON Web Tokens)** for secure authentication
- **Bcrypt** for password hashing
- **Mongoose** for interacting with MongoDB using JavaScript

#### Data Models and Database Schema

Key data models and database schemas include:
- **Student Schema:** Contains fields such as name, email, password, and enrolled courses.
- **Instructor Schema:** Includes name, email, password, and course details.
- **Course Schema:** Comprises course name, description, instructor information, and media content.

### Database

The database for the platform uses **MongoDB**, a NoSQL database that allows for the storage of unstructured and semi-structured data. It stores course content, user data, and other relevant information.

## Usage Instructions

1. Navigate to the front-end application in your browser.
2. Sign up or log in using your email and password.
3. Explore available courses, add them to your wishlist or cart, and purchase them as needed.
4. Instructors can create and manage their courses through their dashboard.



---

