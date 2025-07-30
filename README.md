# QuickCart

## E-commerce Web Application

Deployed Link: (#https://mern-stack-exercise-qdcp.vercel.app/)

## Table of Contents

* [Description](#description)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
    * [Environment Variables](#environment-variables)
    * [Running the Application](#running-the-application)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Deployment](#deployment)
* [Links](#links)
* [License](#license)
* [Contact](#contact)

---

## Description

QuickCart is a modern and intuitive e-commerce web application designed to facilitate seamless online buying and selling experiences. It serves as a platform where users can effortlessly browse and purchase products, while sellers can efficiently manage their product inventories. The application is built upon fundamental Create, Read, Update, and Delete (CRUD) operations for comprehensive data management and features streamlined user authentication via Google. QuickCart aims to provide a robust, scalable, and user-friendly online marketplace.

## Features

QuickCart offers a comprehensive set of functionalities for both buyers and sellers:

* **Product Browse & Search:** Users can effortlessly explore a wide range of products with robust search, filtering, and sorting options.
* **Shopping Cart Functionality:** A user-friendly shopping cart allows buyers to add, remove, and adjust quantities of products before checkout.
* **Secure Google Authentication:** Users can easily sign up and log in using their Google accounts, powered by Clerk, ensuring a secure and streamlined entry.
* **Guest Checkout:** Users can complete purchases without needing to sign in or register an account.
* **User Profiles:** Registered users have access to personalized profiles and can view their past activities.
* **Seller Dashboard:** Dedicated access for sellers to add new products, update existing listings, and remove products from the inventory using intuitive forms.
* **Seamless Checkout Process:** A guided checkout flow ensures users can quickly enter shipping details and place orders.
* **Responsive Design:** The application is built with Tailwind CSS, ensuring a consistent and optimized user experience across various devices.
* **Inquiry Feature:** Users can send direct messages to the administrator regarding specific products, with product details dynamically pre-filled.

## Technologies Used

QuickCart is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, complemented by modern tools and services:

* **Frontend:**
    * [React.js](https://react.dev/): A JavaScript library for building user interfaces.
    * [Next.js](https://nextjs.org/): A React framework providing server-side rendering (SSR), static site generation (SSG), and routing.
    * [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development and responsive design.
    * [Clerk](https://clerk.com/): A developer-first authentication and user management platform for Google authentication.
    * State Management (e.g., React Context API or Redux): For managing global application state.
    * Image Handling (e.g., Cloudinary or similar): For efficient product image storage and delivery.

* **Backend:**
    * [Node.js](https://nodejs.org/): A JavaScript runtime built on Chrome's V8 JavaScript engine.
    * [Express.js](https://expressjs.com/): A minimalist web framework for Node.js, used for building RESTful APIs.

* **Database:**
    * [MongoDB](https://www.mongodb.com/): A flexible, document-oriented NoSQL database.
    * [Mongoose](https://mongoosejs.com/): An ODM (Object Data Modeling) library for MongoDB and Node.js.

* **Deployment:**
    * [Vercel](https://vercel.com/): A cloud platform optimized for Next.js applications, offering continuous deployment and serverless functions.

## Getting Started

Follow these instructions to set up and run QuickCart on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

* [Node.js](https://nodejs.org/en/download/) (v18.x or later recommended)
* [npm](https://www.npmjs.com/get-npm) (comes with Node.js) or [Yarn](https://yarnpkg.com/getting-started/install)
* [MongoDB](https://www.mongodb.com/try/download/community) (Community Server) or access to a MongoDB Atlas cluster.
* A [Clerk](https://clerk.com/) account for authentication setup.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Adityaaj18/mern-stack-exercise.git](https://github.com/Adityaaj18/mern-stack-exercise.git)
    cd mern-stack-exercise
    ```

2.  **Install Frontend Dependencies:**
    Navigate to the frontend directory (e.g., `client` or `frontend`) and install dependencies:
    ```bash
    cd frontend # or your client-side directory name
    npm install # or yarn install
    ```

3.  **Install Backend Dependencies:**
    Navigate to the backend directory (e.g., `server` or `backend`) and install dependencies:
    ```bash
    cd ../backend # or your server-side directory name
    npm install # or yarn install
    ```

### Environment Variables

Both the frontend and backend require environment variables for configuration. Create a `.env` file in both the frontend and backend root directories.

#### Backend (`backend/.env`):
