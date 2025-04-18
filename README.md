# 🚀 Next.js Micro SaaS Template

[![Status: In Development](https://img.shields.io/badge/status-in--development-blue.svg)]()

---

## ✨ Overview

Welcome to the **Next.js Micro SaaS Template**! This project provides a solid foundation for building scalable micro SaaS applications using the latest technologies. Built with [Next.js](https://nextjs.org/), it leverages **auth.js** for secure authentication, **Firebase Firestore** for real-time database functionality, and integrates **Stripe** for payment processing. This template was developed during the [Rocketseat Micro SaaS Challenge](https://rocketseat.com.br/) event, which took place from **April 14th to April 17th**.

---

## 🎯 Project Features

- **Next.js Framework:** Benefit from server-side rendering, static site generation, and API routes.
- **Authentication with auth.js:** Secure, flexible user authentication.
- **Firebase Firestore:** Real-time, scalable database functionality.
- **Stripe Integration:** Seamless payment processing.
- **Modular Architecture:** A scalable codebase designed for micro SaaS applications.
- **Responsive UI:** A modern, fully responsive user interface.
- **Cloud Ready:** Easily deployable on platforms like Vercel or Netlify.
- **Comprehensive Documentation:** In-depth guides on project setup, API usage, and deployment.

---

## 🔧 Technologies & Tools

- **Framework:** [Next.js](https://nextjs.org/)
- **Authentication:** [auth.js](https://authjs.dev/)
- **Database:** [Firebase Firestore](https://firebase.google.com/docs/firestore)
- **Payments:** [Stripe](https://stripe.com/)
- **Styling:** Tailwind CSS, CSS Modules, or your preferred styling method.
- **Code Quality:** ESLint, Prettier, and testing frameworks.

---

## 🏁 Getting Started

### Prerequisites

- **Node.js** (version 14+)
- **npm** or **yarn**
- **Git**
- A [Firebase](https://firebase.google.com/) account with Firestore enabled.
- A [Stripe](https://stripe.com/) account.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/nextjs-micro-saas-template.git
   cd nextjs-micro-saas-template
   ```

2. **Install Dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set Up Environment Variables**

   Create a `.env.local` file in the project's root by copying the provided `.env.example` and then updating it with your credentials:

   ```bash
   cp .env.example .env.local
   ```

   Example `.env.local` content:
   ```
   AUTH_SECRET=

   AUTH_GOOGLE_ID=
   AUTH_GOOGLE_SECRET=

   FIREBASE_PROJECT_ID=
   FIREBASE_CLIENT_EMAIL=
   FIREBASE_PRIVATE_KEY_BASE64=

   STRIPE_SECRET_KEY=
   NEXT_PUBLIC_STRIPE_PUB_KEY=
   STRIPE_PRODUCT_PRICE_ID=
   STRIPE_SUBSCRIPTION_PRICE_ID=
   STRIPE_WEBHOOK_SECRET=

   MERCADO_PAGO_ACCESS_TOKEN=
   NEXT_PUBLIC_MERCADO_PAGO_PUBLIC_KEY=
   MERCADO_PAGO_WEBHOOK_SECRET=

   RESEND_API_KEY=
   ```

4. **Run the Development Server**

   Start the Next.js development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Access the Application**

   Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

---

## 🚀 Deployment

Deploying your Next.js project is simple. This template is optimized for [Vercel](https://vercel.com/), but it can also be deployed on other platforms like Netlify or any Node.js-compatible server.

- **Vercel Deployment:**  
  Push your repository to GitHub and import it into Vercel. The platform will automatically build and deploy your application.

- **Other Platforms:**  
  Refer to the [Next.js Deployment Documentation](https://nextjs.org/docs/deployment) for further options and best practices.

---

## 🌟 Acknowledgments

- Thanks to [Rocketseat](https://rocketseat.com.br/) for hosting the Micro SaaS Challenge event.