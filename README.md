<<<<<<< HEAD
# BWU-Kart
BWU-Kart a web-based marketplace built for college and university students to buy and sell educational products within their campus community. It simplifies the exchange of used items like textbooks, lab equipment, calculators, and other study-related tools — making education more affordable and accessible for students.
Problem Statement - 
Students often struggle to find affordable study materials, tools, or gadgets, especially when they're only needed for a short time. Meanwhile, others have unused items they’d like to sell—but there’s no dedicated system in place for that.
Solution (How BWU-Kart helps) - 
Campus Kart solves this by creating a trusted, campus-specific marketplace where students can connect to buy and sell items like books, lab equipment, calculators, and more—safely and efficiently.
=======
<<<<<<< HEAD
# BWU-Kart
=======
Frontend - React.js , Typescript , CSS , HTML 
Serverless Backend - Firebase Authentication , Firebase Firestore
Deployment - Vercel
Other Tools - Git (Tracking code changes) , VS code (Code Editor)

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

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

### Security

Firebase security rules require further development before the application can be considered production-ready.

## 🗺️ Future Roadmap

The long-term goal is to evolve B-Kart from a hackathon prototype into a complete student marketplace.

## 🎓 Origin of the Project

B-Kart was created as a **university-focused hackathon project** and was also my first major web development project.

The initial goal was not to build a complete commercial e-commerce platform, but to demonstrate the concept of a marketplace designed specifically for students.

The project is being retained as a foundation for future development and architectural improvements.

---

## 👨‍💻 Author

**Ratnesh**

Engineering Student

GitHub:  
https://github.com/Ratnesh-Coder

---

## 📄 License

This project is currently maintained as a personal/student project.

If a formal open-source license is added in the future, the license information will be updated here.

---

### B-Kart

**A marketplace built around the needs of students.**

> From a hackathon prototype to a complete student marketplace — this is the beginning of B-Kart.
