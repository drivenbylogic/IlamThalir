# 🌱 IlamThalir

**Official website source for Ilam Thalir Social Service Trust**

A full-stack, production-ready web platform built to **showcase community initiatives, communicate impact, document events, recruit volunteers, and accept donations** across Tamil Nadu.  
The project emphasizes **transparency, simplicity, and long-term maintainability**, enabling a scalable digital presence for social good.

---

## 📌 Overview

This repository contains the source code for the Ilam Thalir NGO website and web application.  
It is designed as a **modular, scalable system** that avoids unnecessary complexity while remaining production-grade and extensible.

The platform serves:
- The general public (impact & events)
- Volunteers (discovery & registration)
- Administrators (content, events, donations management)

---

## 🎯 Project Objectives

The platform is built around four core objectives (in priority order):

### 1. Communicate Impact
Clearly showcase the NGO’s mission, impact metrics, stories, testimonials, and media to build trust and credibility.

### 2. Build a Track Record of Events
Maintain a transparent and verifiable record of past and upcoming events with descriptions, photos, and status tracking.

### 3. Recruit Volunteers
Enable interested individuals to discover the NGO’s work and register as volunteers with minimal friction.

### 4. Accept Donations
Provide a secure, simple one-time donation flow with proper record-keeping and admin visibility.

---

## 🧱 Architecture Philosophy

- **Modular monolith** (clean separation without microservice overhead)
- **Backend-first, IAM-driven design**
- **Relational data model** for integrity and reporting
- **Admin-only authentication (MVP)**
- **SEO-friendly frontend rendering**

The system is intentionally designed to scale feature-wise without requiring architectural rewrites.

---

## 🛠️ Tech Stack

### Frontend
- **Next.js** (React with SSR)
- **TypeScript**
- **Tailwind CSS**

### Backend
- **Node.js**
- **Express / API Routes**
- Modular service-based structure

### Database
- **PostgreSQL**
- Relational, normalized schema

### Authentication
- Session-based authentication using **HTTP-only cookies**
- Secure password hashing with **bcrypt**

### Payments
- One-time donation flow
- Payment gateway integration (configurable)

### Media Storage
- External object storage (e.g., **Cloudinary**, **AWS S3**)

---

## 🔐 Security Considerations

- HTTP-only secure cookies for sessions
- Role-based access control for admin routes
- Password hashing with bcrypt
- No sensitive data exposed to the client
- Payment logic isolated to the backend

---

## 🚀 MVP Scope

The MVP focuses strictly on core functionality:

- Public impact & events pages
- Volunteer registration
- One-time donations
- Admin CRUD for content, events, volunteers, and donations

Advanced features are intentionally deferred to avoid overengineering.

---

## 🗺️ Future Enhancements

Planned (but out of MVP scope):

- Volunteer login & role expansion
- Event registration & attendance tracking
- Impact timelines & downloadable reports
- Donation analytics & summaries
- Role-based admin permissions
- Improved reporting & exports

---

## 🧠 Design Principles

- **Clarity over cleverness**
- **Minimal IAM, not enterprise IAM**
- **Structured data over schema-less shortcuts**
- **Trust-first UX**
- **Ship MVP → iterate with intent**

---

## 📄 License

This project is developed for NGO and social service use.  
It may be adapted or extended for other non-profit organizations with similar requirements.

---

## 🤝 Contributions

This repository is currently maintained by a single developer.  
Contribution guidelines may be added in the future as the project evolves.
