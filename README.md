
<div align="center">

# 🛒 Grocery Store Application

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-14.x-black?style=for-the-badge&logo=next.js" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Strapi-4.x-8e75ff?style=for-the-badge&logo=strapi" alt="Strapi"/>
  <img src="https://img.shields.io/badge/Tailwind-3.x-38bdf8?style=for-the-badge&logo=tailwindcss" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/PayPal-Integration-00457c?style=for-the-badge&logo=paypal" alt="PayPal"/>
</p>

A modern, full-stack e-commerce application for grocery shopping with a sleek UI and robust backend.

</div>

## 📋 Overview

This Grocery Store application provides a complete online shopping experience with product browsing, cart management, user authentication, and secure checkout. Built with modern technologies for performance, scalability, and user experience.

## 🏗️ Project Structure

The application is divided into two main components:

### Frontend (Next.js)

- **Modern UI**: Built with Next.js 14 and Tailwind CSS
- **Responsive Design**: Optimized for all device sizes
- **Component Library**: Leverages Radix UI and Headless UI components
- **Payment Integration**: Secure checkout with PayPal

### Backend (Strapi)

- **Content Management**: Strapi headless CMS for product and category management
- **Authentication**: Secure user registration and login
- **Media Management**: Cloudinary integration for image storage
- **Database**: PostgreSQL for data persistence

## ✨ Features

- 🔐 User authentication and account management
- 🏪 Product browsing by categories
- 🔍 Product search and filtering
- 🛒 Shopping cart functionality
- 💳 Secure checkout process
- 📱 Responsive design for all devices
- 🌙 Light/dark mode support
- 🖼️ Image optimization with Cloudinary

## 🚀 Getting Started

### Prerequisites

- Node.js (>=18.0.0 <=20.x.x)
- npm or yarn
- PostgreSQL database (for production)

### Installation

#### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd grocery-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file based on `.env.example` with your configuration

4. Start the development server:
   ```bash
   npm run develop
   # or
   yarn develop
   ```

#### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd grocery-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env.local` file with the following variables:
   ```
   NEXT_PUBLIC_BACKEND_BASE_URL=http://localhost:1337/api
   NEXT_PUBLIC_PAYPAL_CLIENT_ID=your_paypal_client_id
   ```

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🌐 Deployment

### Frontend Deployment

The Next.js frontend can be easily deployed on Vercel:

1. Push your code to a GitHub repository
2. Import the project in Vercel
3. Configure the environment variables
4. Deploy

### Backend Deployment

The Strapi backend can be deployed on various platforms:

1. Set up a PostgreSQL database
2. Configure environment variables for production
3. Build the Strapi application:
   ```bash
   npm run build
   # or
   yarn build
   ```
4. Start the production server:
   ```bash
   npm run start
   # or
   yarn start
   ```

## 🔧 Environment Variables

### Backend (.env)

```
HOST=0.0.0.0
PORT=1337
APP_KEYS=your_app_keys
API_TOKEN_SALT=your_api_token_salt
ADMIN_JWT_SECRET=your_admin_jwt_secret
JWT_SECRET=your_jwt_secret

# Database
DATABASE_CLIENT=postgres
DATABASE_HOST=your_database_host
DATABASE_PORT=5432
DATABASE_NAME=your_database_name
DATABASE_USERNAME=your_database_username
DATABASE_PASSWORD=your_database_password
DATABASE_SSL=true

# Cloudinary
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
```

### Frontend (.env.local)

```
NEXT_PUBLIC_BACKEND_BASE_URL=https://your-backend-url.com/api
NEXT_PUBLIC_PAYPAL_CLIENT_ID=your_paypal_client_id
```

## 📚 Tech Stack

### Frontend
- Next.js 14
- React 18
- Tailwind CSS
- Radix UI components
- Headless UI
- Axios
- PayPal React SDK

### Backend
- Strapi 4
- PostgreSQL
- Cloudinary for media storage

## 📝 License

This project is licensed under the MIT License.

---

<div align="center">

### 🌟 Happy Shopping! 🌟

</div>
