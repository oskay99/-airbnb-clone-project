# 🏡 Airbnb Clone Project

## Overview
This project is a full-stack clone of the Airbnb platform. It allows users to browse property listings, view detailed property information, and complete bookings.  
The project is built to simulate a production-grade booking system with authentication, payments, and responsive UI.

## 🎯 Project Goals
- Build a responsive full-stack web app with a seamless booking flow.
- Learn to integrate frontend and backend through APIs.
- Practice team collaboration using GitHub version control.
- Gain hands-on experience with modern web technologies.

## 🧰 Tech Stack
**Frontend:** Next.js (React), Tailwind CSS  
**Backend:** Node.js / Next.js API Routes  
**Database:** PostgreSQL (via Prisma ORM)  
**Authentication:** NextAuth.js  
**Deployment:** Vercel + Supabase  
**Version Control:** Git & GitHub  

## 👥 Contributors
- [Your Name] – Frontend Developer
- [Add other team members and roles]

- ## 🎨 UI/UX Design Planning

### 🧭 Design Goals
The primary goal of the Airbnb Clone’s UI/UX design is to create a simple, modern, and intuitive interface that enhances the user experience while maintaining visual consistency across devices.

**Key design goals include:**
- Build an intuitive and fast booking flow.
- Maintain consistent visuals across all screens.
- Prioritize mobile responsiveness (mobile-first design).
- Optimize performance for fast loading times.
- Ensure accessibility compliance (WCAG standards).

---

### ⚙️ Key Features
| Feature | Description |
|----------|--------------|
| Property Search & Filter | Allows users to find properties based on location, price, and amenities. |
| Detailed Property Viewing | Displays full property information including images, descriptions, and reviews. |
| Secure Checkout Process | Provides a seamless and secure way to book a stay and confirm payments. |
| User Authentication | Allows users to log in, sign up, and manage their bookings. |
| Responsive Layout | Ensures usability on mobile, tablet, and desktop devices. |

---

### 📱 Primary Pages

| **Page** | **Description** |
|-----------|-----------------|
| **Property Listing View** | Displays a grid of available properties with images, prices, and filters for easy browsing. |
| **Listing Detailed View** | Shows full details about a specific property including photos, host info, amenities, and a booking form. |
| **Simple Checkout View** | A streamlined checkout interface that captures user information, booking dates, and simulates payment confirmation. |

---

### 💡 Importance of User-Friendly Design
A user-friendly design is essential in an online booking system because it directly influences user satisfaction and conversion rates.  

An intuitive layout with clear navigation reduces user friction during booking, helping users quickly find suitable listings and complete reservations with confidence.  
By focusing on **simplicity**, **clarity**, and **consistency**, we ensure the system feels reliable, professional, and enjoyable to use — just like the real Airbnb experience.


### 🎨 Design Properties (from Figma)

#### 🎨 Color Styles
| **Color Name / Token** | **Hex / Value** | **Usage in UI** |
|-------------------------|------------------|-------------------|
| Primary | `#FF5A5F` | Buttons, highlights, primary actions |
| Secondary | `#008489` | Accent elements, links |
| Background | `#FFFFFF` | Page background, card backgrounds |
| Text Primary | `#222222` | Main text, headlines |
| Text Secondary | `#717171` | Subtext, labels, helper text |
| (Add more) | (value) | (usage) |

---

#### ✍️ Typography / Text Styles
| **Text Style / Token** | **Font Family** | **Weight** | **Size** | **Usage / Example** |
|-------------------------|-------------------|-------------|------------|----------------------|
| Heading / Title | Circular | Bold (700) | 32px | Page titles |
| Section Heading | Circular | Bold (700) | 24px | Section headers |
| Body / Paragraph | Circular | Medium (500) | 16px | Main content |
| Secondary Text / Caption | Circular | Book (400) | 14px | Labels, captions |
| (Add more) | (family) | (weight) | (size) | (usage) |

---

### 💡 Why It’s Important to Document Design Properties

Identifying design properties in your mockups is a critical step in the design-to-development pipeline because:

- **Consistency & Cohesion**: Ensures that all UI elements across pages use the exact same colors, fonts, sizes, and spacing.  
- **Efficient Implementation**: Developers can directly plug the tokens into CSS, Tailwind config, or design systems, reducing guesswork and manual adjustments.  
- **Scalability**: As your app grows, having a documented design system helps scale UI development without inconsistencies.  
- **Collaboration & Handoff**: Facilitates clear communication between designers and developers — both sides refer to the same defined tokens.  
- **Accessibility & Readability**: Knowing font sizes and contrast levels helps maintain accessible UI (e.g. enough contrast for readability).  

---

## 👥 Project Roles and Responsibilities

A successful full-stack project like the **Airbnb Clone** requires clearly defined roles and responsibilities to ensure efficiency, accountability, and collaboration across all areas — from design to deployment.

Below is the breakdown of each key project role and their contributions.

---

### 🧭 Project Manager
**Key Responsibilities:**
- Oversee the overall project timeline and delivery.
- Coordinate tasks and communication between team members.
- Track milestones and ensure objectives are met on schedule.
- Manage risk, changes, and scope during the project lifecycle.

**Contribution:**
The Project Manager ensures alignment between team goals and project outcomes, keeping all tasks organized and delivered on time.

---

### 💻 Frontend Developers
**Key Responsibilities:**
- Implement responsive UI components using React/Next.js and Tailwind CSS.
- Integrate frontend with backend APIs for data rendering.
- Maintain consistency with the Figma design system.
- Ensure accessibility and performance optimization.

**Contribution:**
Frontend Developers bring the user interface to life — building the core user experience and making the design functional and interactive.

---

### ⚙️ Backend Developers
**Key Responsibilities:**
- Develop and maintain RESTful/GraphQL APIs.
- Design and manage database models using Prisma and PostgreSQL.
- Implement business logic for listings, bookings, and authentication.
- Handle data validation, security, and performance optimization.

**Contribution:**
Backend Developers ensure the application’s functionality, data integrity, and performance behind the scenes — powering the core booking system.

---

### 🎨 Designers
**Key Responsibilities:**
- Create wireframes, mockups, and prototypes in Figma.
- Define color schemes, typography, and design tokens.
- Ensure usability, accessibility, and visual consistency.
- Collaborate with developers for accurate implementation.

**Contribution:**
Designers shape the visual identity and user journey of the Airbnb Clone, ensuring an engaging and intuitive experience for all users.

---

### 🧪 QA / Testers
**Key Responsibilities:**
- Write and execute test cases for UI and API functionalities.
- Perform unit, integration, and regression testing.
- Identify and document bugs and usability issues.
- Validate that new features do not break existing functionality.

**Contribution:**
QA/Testers maintain application quality and stability, ensuring a bug-free and reliable user experience.

---

### ☁️ DevOps Engineers
**Key Responsibilities:**
- Set up CI/CD pipelines for automated testing and deployment.
- Manage server infrastructure and environment variables.
- Configure production environments (Vercel, Supabase).
- Monitor performance, uptime, and security.

**Contribution:**
DevOps Engineers streamline deployment and ensure the system runs smoothly across all environments — from development to production.

---

### 🧑‍💼 Product Owner
**Key Responsibilities:**
- Define product vision, goals, and feature priorities.
- Communicate user and stakeholder needs to the team.
- Approve features and ensure alignment with business objectives.

**Contribution:**
The Product Owner ensures the product meets real-world user needs and delivers maximum business value.

---

### 🚀 Scrum Master
**Key Responsibilities:**
- Facilitate agile ceremonies (daily stand-ups, sprints, retrospectives).
- Remove blockers and improve team workflow.
- Promote continuous improvement within the team.

**Contribution:**
The Scrum Master enables effective teamwork and ensures that the agile process drives productivity and progress.

---

### ✅ Summary Table

| **Role** | **Primary Focus** | **Key Tools / Deliverables** |
|-----------|-------------------|-------------------------------|
| Project Manager | Coordination & Timeline | Project board, Reports |
| Frontend Developers | UI Implementation | React/Next.js, Tailwind, API integration |
| Backend Developers | Server & Database Logic | Node.js, Prisma, PostgreSQL |
| Designers | Visual Design & UX | Figma, Design Tokens |
| QA / Testers | Quality Assurance | Jest, Manual Testing |
| DevOps Engineers | CI/CD & Infrastructure | GitHub Actions, Vercel |
| Product Owner | Vision & Requirements | Feature Backlog |
| Scrum Master | Team Productivity | Sprint Planning, Stand-ups |



## 📄 License
MIT License
