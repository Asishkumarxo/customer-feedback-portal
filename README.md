# Customer Feedback Portal

A full-stack, responsive Customer Feedback Portal built as part of the **Customer Experience Design & Project Management (CEDP)** curriculum at Centurion University.

This portal enables end-customers to submit multi-category feedback, rate their experience (1–5 stars), and attach screenshots/PDFs. Internal support staff can triage, search, filter, and track ticket lifecycle status in real time.

---

## 📋 Software Requirements Specification (SRS v1.0)

### 1. Purpose
Define functional, UX, and technical architecture for capturing experiential feedback and providing internal support teams with centralized management and resolution tools.

### 2. Scope
- **Customer Facing**: Interactive feedback submission form with 1–5 star rating, category selection, and file attachments (≤ 5MB).
- **Processing Engine**: Automated reference Ticket ID generation (`#CFP-XXXX`) and immediate email receipt dispatch.
- **Staff Facing**: Centralized dashboard with search, multi-facet filtering, status transitions, and resolution analytics.

### 3. User Personas
- **Customer**: Submits feedback, ratings, and attachments; tracks status via email receipts.
- **Support Staff**: Triages tickets, updates statuses, and responds to inquiries.
- **CX Manager**: Reviews satisfaction metrics, resolution SLAs, and trends.

---

## 🚀 Agile User Stories (Sprint 1)

| Story ID | Title | Estimate | Priority | Status |
| :--- | :--- | :---: | :---: | :---: |
| **#101** | Customer Feedback Submission Form with 1–5 Star Rating | 3 SP | High | **Done** |
| **#102** | Multi-Format File Attachment Uploader (Screenshots & PDFs) | 5 SP | Medium | **Sprint** |
| **#103** | Centralized Staff Feedback Triage Queue & Details View | 5 SP | High | **Done** |
| **#104** | Real-Time Keyword Search & Multi-Facet Category Filter | 3 SP | High | **In Progress** |
| **#105** | Ticket Status Transition Workflow (`New` ➔ `In Review` ➔ `Resolved`) | 2 SP | Medium | **Sprint** |
| **#106** | Automated Email Receipt & Tracking Ticket ID Dispatcher | 3 SP | Low | **Backlog** |

---

## 🛠️ Tech Stack
- **Frontend**: React.js, TailwindCSS / CSS Modules, Axios
- **State Management**: React `useState`, `useEffect`
- **Backend / Mock API**: Express.js / DummyJSON REST API
- **Agile Board**: GitHub Projects (Board View)

---

## 👤 Author
- **GitHub**: [@Asishkumarxo](https://github.com/Asishkumarxo)
- **Institution**: Centurion University of Technology and Management
