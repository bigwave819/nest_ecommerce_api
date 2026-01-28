🛒 NestJS E-Commerce API

Secure • Scalable • Production-Ready

A powerful, production-grade E-commerce REST API built with NestJS, designed following industry best practices in security, clean architecture, and DevOps.
This backend powers modern commerce workflows including authentication, product browsing, cart management, orders, and payments.

🚀 Features
🔐 Authentication & Authorization

JWT-based authentication (Access & Refresh Tokens)

Role-based access control (Admin, Customer)

Secure password hashing (bcrypt)

Protected routes with Guards & Decorators

🧑‍💻 User Management

User registration & login

Profile management

Role assignment & permissions

🛍️ Product & Catalog

Browse products

Product categories

Product search & filtering

Admin product CRUD (Create, Update, Delete)

🛒 Cart & Orders

Add/remove products from cart

Create and manage orders

Order status lifecycle (Pending, Paid, Shipped, Completed)

Secure order ownership validation

💳 Payments

Payment intent creation

Order-to-payment linkage

Secure transaction handling

Ready for integration with payment providers (Stripe / Flutterwave / PayPal)

🖼️ Media & Assets

Product image upload

Secure file handling

Cloud-ready storage support

🧱 Architecture

This project follows Clean Architecture and Domain-Driven Design (DDD) principles:

src/
├── auth/
├── users/
├── products/
├── cart/
├── orders/
├── payments/
├── common/
│   ├── guards
│   ├── decorators
│   ├── filters
│   ├── interceptors
│   └── utils
└── main.ts


Modular & scalable

Separation of concerns

Easy to test and extend

🛡️ Security Practices

Helmet for HTTP security headers

Rate limiting & request throttling

Input validation with DTOs & class-validator

Global exception handling

Environment-based secrets management

No sensitive data exposed in responses

⚙️ DevOps & Engineering Practices

Environment-based configuration (.env)

Dockerized for consistent deployments

CI/CD ready (GitHub Actions compatible)

Logging & error tracing

Production-ready build pipeline

Database migrations & versioning

🧪 Testing

Unit testing with Jest

Service-level testing

Clean test separation

🧰 Tech Stack

Backend Framework: NestJS (Node.js)

Database: PostgreSQL / MySQL (via Prisma or TypeORM)

Authentication: JWT

Validation: class-validator

Containerization: Docker

DevOps: CI/CD-ready

Language: TypeScript

🔧 Installation & Setup
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install


Create .env file:

DATABASE_URL=
JWT_SECRET=
JWT_REFRESH_SECRET=
PORT=3000


Run the app:

npm run start:dev

📡 API Documentation

RESTful endpoints

Swagger documentation available at:

/api/docs

🌍 Use Cases

Full e-commerce backend

Mobile app backend (React Native / Flutter)

Web frontend (React / Next.js)

Scalable startup-ready commerce platform

👨‍💻 Author

Hirwa Tresor Christian
Software Engineer | Full-Stack Developer
Focused on building secure, scalable, and impactful systems.

⭐ Final Note

This repository demonstrates real-world engineering discipline, not just functionality.
If you’re reviewing this project as a recruiter or engineer, you’re looking at production mindset code.
