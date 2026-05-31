# SVS Traders - Inventory & Billing Management System

A modern **Inventory and Billing Management System** built for **SVS Traders** to manage billing, stock, returns, analytics, and inventory efficiently.

---

## Features

### Dashboard
- Daily & Monthly Revenue Analytics
- Inventory Value Overview
- Pending Credit Bills
- Return Tracking
- Revenue Trend Graphs
- Real-Time Sales Summary

### Billing System
- Create Bills Quickly
- Barcode/Product Search
- Multiple Product Billing
- Discount Support
- Payment Methods (Cash/Credit)
- Auto Inventory Update
- Invoice Generation
- Customer Details Management
- Daily Sales Report

### Inventory Management
Separate inventory management for:

- Jockey Inventory
- Bevdass Inventory
- Master SVS Inventory

Features:
- Product Search
- Stock Management
- Quantity Tracking
- Product Details View
- Inventory Value Calculation

### Stock Upload
Upload inventory using Excel files:

- Jockey Excel Upload
- Bevdass Excel Upload
- Bulk Product Import
- Automatic Inventory Update

### Returns Management
- Return Processing
- Bill Validation
- Stock Re-adjustment
- Return Tracking

### Reports & Analytics
- Daily Reports
- Monthly Reports
- Sales Analytics
- Brand Performance Tracking

### Authentication
- Secure Login System
- Protected Routes
- Session Management
- Logout Support

---

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS

### Backend / Database
- Supabase

### Deployment
- Vercel

---

## Project Structure

```txt
src/
│── assets/
│── components/
│   ├── billing/
│   ├── dashboard/
│   ├── inventory/
│   ├── reports/
│   ├── shared/
│   └── sidebar/
│
│── context/
│   └── ThemeContext.jsx
│
│── lib/
│   └── supabase.js
│
│── pages/
│   ├── inventory/
│   ├── upload/
│   ├── Analytics.jsx
│   ├── Billing.jsx
│   ├── Dashboard.jsx
│   ├── Login.jsx
│   ├── Reports.jsx
│   ├── Returns.jsx
│   └── Settings.jsx
│
│── App.jsx
│── App.css
│── index.css
│── main.jsx
