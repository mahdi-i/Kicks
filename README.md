# 👟 Kicks - modern shoe store

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-19.2.4-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-6.19.0-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Upstash_Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-4.0-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radix-ui&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## 📋 Project Introduction

**Kicks** is a modern and complete online shoe store built with **Next.js 16** and **TypeScript**. The project is designed with **Next.js 16 Modular Clean Architecture with DDD Approach**, which combines the best practices of clean architecture, domain-driven design, and Next.js modular structure.

> ⚡ **Project Goal**: Deliver a Delightful Shopping Experience with High Performance and Modern UI

---

## 🏗️ Architecture: **Next.js 16 App Router + Modular Clean Architecture (Layered with Domain Focus)**

### 📐 Architecture Layers

| Layer | Route | Responsibility |
|------|------|------|
| **Presentation Layer** | `/app` | Display pages, receive user input |
| **Interface Adapters** | `/core/api-route` | Convert HTTP requests to internal calls |
| **Application Layer** | `/core/features` | Manage scenarios and use cases |
| **Domain Layer** | `/core/prisma` | Entities and business rules |
| **Infrastructure Layer** | `/core/lib` | Communicate with external services |
---

## ✨ Main Features

### 🛍️ Shop Section

- **Display Products** on the Home Page with an Attractive Design
- **Full Product Management** in the Admin Panel
- **Advanced Product Categorization**
- **Smart Search and Filter**

### 📝 Blog System

- **Create Article** with a Smart Multi-Step Form
- **Display Articles** on the Home Page and Dedicated Pages
- **Full Article Management** by Admin
- **Categorizing and Tagging** Articles

### 👤 Authentication and Security

- **Login and Registration System** Secure with OTP
- **One-Time Code** with Storage in Redis (5 Minute Expiration)
- **Password Encryption** with bcryptjs
- **User Session Management** with Next.js

### 🛡️ Admin Panels

- **Admin Panel** Complete with Leveled Access
- **Panel **Personalized** User Account for Each User
- **Analytics Dashboard** with Recharts
- **File Management** with Cloudinary and Uploadthing

---

## 🛠️ Technologies & Tools

| Category | Technologies | Status |
|---------|-------------|--------|
| **⚛️ Core Framework** | ![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=flat-square) · ![React](https://img.shields.io/badge/React-19.2.4-blue?style=flat-square) · ![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=flat-square) | ✅ Active |
| **🎨 Style & UI** | ![Tailwind](https://img.shields.io/badge/Tailwind-4.0-06B6D4?style=flat-square) · ![Radix UI](https://img.shields.io/badge/Radix_UI-Components-161618?style=flat-square) · ![Lucide](https://img.shields.io/badge/Lucide-Icons-5e5e5e?style=flat-square) | ✅ Active
| **🗄️ database and ORM** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=flat-square) · ![Prisma](https://img.shields.io/badge/Prisma-6.19.0-2D3748?style=flat-square) · ![Redis](https://img.shields.io/badge/Redis-Upstash-FF4438?style=flat-square) | ✅ Active
| **☁️ Storage** | ![Cloudinary](https://img.shields.io/badge/Cloudinary-Images-3448C5?style=flat-square) · ![Uploadthing](https://img.shields.io/badge/Uploadthing-Files-000000?style=flat-square) | ✅ Active
| **🔐 Authentication** | ![bcryptjs](https://img.shields.io/badge/bcryptjs-Encryption-4B32C3?style=flat-square) · ![Resend](https://img.shields.io/badge/Resend-OTP_Email-000000?style=flat-square) | ✅ Active |
| **📊 Components** | ![Swiper](https://img.shields.io/badge/Swiper-Slider-6332F6?style=flat-square) · ![Recharts](https://img.shields.io/badge/Recharts-Charts-22b5bf?style=flat-square) · ![Vaul](https://img.shields.io/badge/Vaul-Drawer-000000?style=flat-square) · ![Sonner](https://img.shields.io/badge/Sonner-Toast-000000?style=flat-square) | ✅ Active
| **🛠️ development tools** | ![ESLint](https://img.shields.io/badge/ESLint-Linting-4B32C3?style=flat-square) · ![TSX](https://img.shields.io/badge/TSX-Scripts-3178C6?style=flat-square) | ✅ Active
