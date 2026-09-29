# 🛒 B-Kart

### A Student-Centric Marketplace for University Communities

**B-Kart** is a student-focused online marketplace designed to make buying and selling products within a university community simple, accessible, and convenient.

The project was originally developed as a **hackathon prototype** to demonstrate the concept of a campus-focused marketplace. It was built as my first web development project using **React, TypeScript, Tailwind CSS, and Firebase**.

> **Project Status:** 🚧 Prototype / Hackathon Version

---

## 📌 About the Project

Students frequently need products such as books, stationery, electronics, bicycles, laboratory equipment, hostel supplies, sports equipment, and other everyday items.

Traditional marketplaces are not specifically designed around the needs of a university campus.

**B-Kart** explores the idea of creating a dedicated marketplace where students can discover and list products relevant to their campus community.

The prototype focuses on:

- 🛍️ Browsing products
- 🔎 Searching for products
- 🗂️ Browsing products by category
- 📦 Viewing product details
- 🏷️ Listing products for sale
- 🔐 Google authentication
- ☁️ Firebase integration
- 📱 Responsive web interface

---

## 🎯 Project Goals

The primary goals of B-Kart are:

1. Create a marketplace specifically for students.
2. Make buying and selling within a university community easier.
3. Provide a simple and accessible user interface.
4. Demonstrate how modern web technologies can be combined to build a marketplace application.
5. Establish a foundation that can later be expanded into a complete production-ready platform.

---

## ✨ Current Features

### 🏠 Product Discovery

- Browse available products.
- Product cards with images, titles, prices, and categories.
- Product detail pages.
- Category-based navigation.
- Basic product search.

### 🔐 Authentication

The prototype includes Firebase Authentication with Google Sign-In.

### 🏷️ Sell Products

Users can enter basic product information and submit a product through the selling interface.

### 🔥 Firebase Integration

The project includes Firebase integration for:

- Firebase Authentication
- Cloud Firestore
- Firebase Storage

### 🎨 User Interface

The application uses:

- Responsive layouts
- Tailwind CSS
- Reusable React components
- Navigation and category menus
- Product-focused UI

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **React** | Frontend UI |
| **TypeScript** | Type-safe JavaScript development |
| **Vite** | Development server and build tool |
| **React Router** | Client-side routing |
| **Tailwind CSS** | Styling and responsive UI |
| **Firebase Authentication** | User authentication |
| **Cloud Firestore** | Product/database layer |
| **Firebase Storage** | Image storage foundation |
| **ESLint** | Code quality and linting |
| **Git & GitHub** | Version control |

---

## 🏗️ Project Structure

```text
B-Kart/
│
├── public/
│   ├── 404.html
│   ├── index.html
│   └── vite.svg
│
├── src/
│   │
│   ├── assets/
│   │   ├── BWUKart.png
│   │   ├── arrow.png
│   │   ├── google.png
│   │   ├── guitar.png
│   │   ├── lens.png
│   │   ├── phone.png
│   │   └── search.png
│   │
│   ├── components/
│   │   ├── Footer.tsx
│   │   ├── Home.tsx
│   │   ├── Login.tsx
│   │   ├── Main.tsx
│   │   ├── Menubar.tsx
│   │   ├── Navbar.tsx
│   │   ├── details.tsx
│   │   └── sell.tsx
│   │
│   ├── data/
│   │   └── fakeproduct.ts
│   │
│   ├── firebase/
│   │   └── setup.tsx
│   │
│   ├── App.css
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
│
├── firestore.rules
├── firestore.indexes.json
├── storage.rules
├── tailwind.config.js
├── postcss.config.js
├── vite.config.ts
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
├── eslint.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm
- Git

You can verify your installation with:

```bash
node --version
npm --version
git --version
```

---

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/Ratnesh-Coder/B-Kart.git
```

Navigate into the project:

```bash
cd B-Kart
```

Install dependencies:

```bash
npm install
```

---

## 🔐 Firebase Configuration

B-Kart uses Firebase services for authentication, database functionality, and storage.

Create a `.env` file in the project root:

```env
VITE_MY_API_KEY=your_firebase_api_key
VITE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_PROJECT_ID=your_project_id
VITE_STORAGE_BUCKET=your_project.appspot.com
VITE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_APP_ID=your_app_id
```

> **Important:** Never commit private credentials, service-account keys, or other sensitive Firebase configuration files to GitHub.

The exact environment variable names should match the Firebase configuration used in `src/firebase/setup.tsx`.

---

## ▶️ Running the Project

Start the development server:

```bash
npm run dev
```

Vite will provide a local development URL, normally:

```text
http://localhost:5173
```

Open the URL in your browser.

---

## 🧪 Building for Production

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

## 🔄 Application Flow

The current prototype follows this general flow:

```text
                    B-Kart
                       │
             ┌─────────┴─────────┐
             │                   │
          Browse                Sell
             │                   │
             ↓                   ↓
        Product List       Product Form
             │                   │
             ↓                   ↓
      Product Details       Firebase
             │
             ↓
        View Product
```

Authentication is handled through Firebase:

```text
User
  │
  ↓
Login
  │
  ↓
Google Authentication
  │
  ↓
Firebase Auth
```

---

## 🗂️ Product Categories

The prototype includes categories intended for common university requirements, including:

- Books
- Electronics
- Laboratory Equipment
- Stationery
- Furniture
- Hostel Supplies
- Cycles
- Accessories
- Sports Equipment
- Medical/First-Aid Items
- Bikes

---

## 📸 Prototype

The project was initially created as a **hackathon demonstration**, with the primary focus being on validating the concept and presenting the user experience.

The current implementation should therefore be considered a **prototype rather than a production-ready e-commerce platform**.

---

## 🚧 Current Limitations

The current version intentionally remains a prototype and has several areas that require further development.

### Product Management

- Product data architecture needs further consolidation.
- Product editing and deletion are not fully implemented.
- Seller ownership needs to be properly associated with products.
- Product validation needs improvement.

### Images

The prototype currently uses temporary browser image URLs in parts of the selling workflow. A production implementation should use Firebase Storage for persistent image storage.

### Marketplace Features

The following are planned but are not fully implemented in the current prototype:

- Shopping cart
- Checkout
- Orders
- Order history
- Delivery tracking
- Seller dashboard
- Product moderation
- Admin dashboard
- Product reviews
- Notifications

### Security

Firebase security rules require further development before the application can be considered production-ready.

---

## 🗺️ Future Roadmap

The long-term goal is to evolve B-Kart from a hackathon prototype into a complete student marketplace.

### Phase 1 — Foundation

- [ ] Refactor project architecture
- [ ] Create consistent TypeScript data models
- [ ] Improve Firebase configuration
- [ ] Implement production-ready Firestore rules
- [ ] Implement production-ready Storage rules

### Phase 2 — User System

- [ ] User profiles
- [ ] Student verification
- [ ] User roles
- [ ] Seller profiles
- [ ] My Listings

### Phase 3 — Product System

- [ ] Persistent image uploads
- [ ] Product categories
- [ ] Product conditions
- [ ] Multiple product images
- [ ] Product editing
- [ ] Product deletion
- [ ] Product moderation

### Phase 4 — Marketplace

- [ ] Shopping cart
- [ ] Checkout
- [ ] Order creation
- [ ] Order history
- [ ] Order status
- [ ] Delivery workflow

### Phase 5 — Administration

- [ ] Admin dashboard
- [ ] Product approval/rejection
- [ ] User management
- [ ] Order management
- [ ] Reports and moderation tools

### Phase 6 — Production

- [ ] Performance optimization
- [ ] Security audit
- [ ] Error handling
- [ ] Automated testing
- [ ] Production deployment
- [ ] Monitoring and analytics

---

## 🔒 Security

Security is an important part of the planned production version of B-Kart.

The application is intended to use:

- Firebase Authentication
- Firestore Security Rules
- Firebase Storage Security Rules
- Role-based authorization
- Seller ownership verification
- Input validation
- Secure environment configuration

> The current GitHub repository represents a prototype and should not be treated as a production-ready marketplace.

---

## 🎓 Origin of the Project

B-Kart was created as a **university-focused hackathon project** and was also my first major web development project.

The initial goal was not to build a complete commercial e-commerce platform, but to demonstrate the concept of a marketplace designed specifically for students.

The project is being retained as a foundation for future development and architectural improvements.

---

## 📚 What I Learned

Building B-Kart helped me gain practical experience with:

- React component development
- TypeScript
- Client-side routing
- Tailwind CSS
- Firebase Authentication
- Cloud Firestore
- Firebase Storage
- Form handling
- State management
- Responsive web design
- Git and GitHub
- Project architecture
- Debugging and troubleshooting

---

## 👨‍💻 Author

**Ratnesh**

Engineering Student & Developer

GitHub:  
https://github.com/Ratnesh-Coder

---

## 📄 License

This project is currently maintained as a personal/student project.

If a formal open-source license is added in the future, the license information will be updated here.

---

## ⭐ Acknowledgements

Built with:

- React
- TypeScript
- Vite
- Tailwind CSS
- Firebase

---

### B-Kart

**A marketplace built around the needs of students.**

> From a hackathon prototype to a complete student marketplace — this is the beginning of B-Kart.
