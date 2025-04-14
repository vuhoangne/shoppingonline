# 🛒 Shopping Online

**Shopping Online** is a full-featured e-commerce web application that allows users to browse products, add items to a cart, and place orders. The system includes a modern frontend interface, a powerful backend API, and a secure user management system with role-based access.

---

## 🚀 Features

- User registration and login
- Product listing and product detail pages
- Shopping cart and order placement
- User and admin order management
- Product and category management (admin panel)
- Sales statistics dashboard
- JWT-based authentication and role-based authorization

---

## 🛠 Technologies Used

### 🔧 Backend (`shoppingAPI`)
- **Node.js** – JavaScript runtime
- **NestJS / Express** – Backend framework (choose one)
- **TypeScript** – Primary language
- **MySQL** – Relational database
- **JWT** – Authentication tokens
- **Swagger** – API documentation

### 🎨 Frontend (`shoppingFrontend`)
- **React (Next.js)** – Modern frontend framework
- **TypeScript** – Static typing for reliability
- **Tailwind CSS** – Utility-first CSS framework
- **React Query** – Server state management
- **React Hook Form** – Efficient form handling

---

## 📦 Installation

### 💻 System Requirements
- Node.js >= 18.x
- MySQL >= 8.x
- Yarn or npm

### 🔙 Backend Setup (`shoppingAPI`)

```bash
cd shoppingAPI
yarn install
cp .env.example .env  # Create environment config
# Edit DB credentials, JWT_SECRET, etc. in .env
yarn prisma migrate dev  # Run database schema migration
yarn start:dev           # Start backend server 
```
🧪 Testing
Backend Tests
```bash 
cd shoppingFrontend
yarn install
cp .env.example .env  # Create frontend env file
# Set API_URL pointing to your backend
yarn dev  # Start development server
```
Frontend Tests
```bash
cd shoppingFrontend
yarn test
```
🏗 Project Structure
🔙 Backend (shoppingAPI)
```bash
src/
├── auth/           # Authentication & Authorization
├── users/          # User management
├── products/       # Product management
├── categories/     # Category management
├── orders/         # Order processing
├── dashboard/      # Sales statistics
├── app.module.ts   # Main app module
└── main.ts         # Application entry point
```
🖥 Frontend (shoppingFrontend)
```bash
src/
├── app/            # Next.js App Router structure
│   ├── auth/       # Login / Register pages
│   ├── cart/       # Shopping cart
│   ├── products/   # Product listing & details
│   ├── admin/      # Admin dashboard
│   └── orders/     # Order history & details
├── components/     # Reusable components
├── services/       # API services
└── styles/         # Global styles
---
```
🔒 Security
JWT Authentication

Role-based Access Control (Admin, User)

Input validation & sanitization

CORS Protection

API Rate Limiting

📈 Performance Optimizations
Database indexing and pagination

Popular product caching

Lazy loading product images

Code splitting by page

Optimized MySQL schema design
---
🤝 Contributing
Fork the repository

Create a new branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request for review
---
📝 License
This project is licensed under the MIT License – see the LICENSE file for details.
---
👥 Author
Lê Nguyễn Vũ Hoàng
Full-stack & backend developer
Contact: vuhoangdz2003@gmail.com
