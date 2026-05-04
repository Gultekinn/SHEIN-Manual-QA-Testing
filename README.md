# 🛍️ SHEIN E-Commerce Platform — Manual QA Testing Project

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Test Cases](https://img.shields.io/badge/Test%20Cases-27-blue)
![Pass Rate](https://img.shields.io/badge/Pass%20Rate-92.6%25-success)
![Type](https://img.shields.io/badge/Testing-Manual%20QA-orange)

> A professional manual QA testing project conducted on the SHEIN e-commerce web application, covering functional, UI/UX, and regression testing scenarios across the full user journey — from landing page to checkout.

---

## 📋 Project Overview

| Field | Details |
|---|---|
| **Target URL** | [us.shein.com](https://us.shein.com) |
| **Project Version** | v2.0 |
| **QA Engineer** | Gültekin Əzizova |
| **Role** | Software QA Tester |
| **Test Type** | Manual Functional Testing |
| **Browser** | Google Chrome v124+ |
| **OS** | Windows 11 Pro |
| **Network** | High-speed Wi-Fi |
| **Hardware** | 1TB Lexar SSD |
| **Date** | 2026 |

---

## 🎯 Testing Scope & Modules

| Module | Description |
|---|---|
| 🏠 **Home Page** | Informational banners, logo redirection, search functionality |
| 🔐 **Login Page** | Sign-in, registration, forgot password, sign-out flows |
| 🛒 **Shopping Cart** | Add items, quantity updates, item removal |
| 📄 **Product Detail Page** | Add to cart with size/color/quantity selection |
| 🛍️ **Shopping Page** | Cart management, checkbox, similar items, wishlist move |
| ❤️ **Favorites Page** | Real-time favorites counter update |

---

## 🧪 Methodologies & Techniques Applied

- **Black Box Testing** — Functional testing performed entirely via the UI
- **Positive & Negative Testing** — Validated expected behavior and error handling
- **Boundary Value Analysis (BVA)** — Tested quantity limits (e.g., Qty 99) and stock messages
- **Error Guessing** — Targeted form validation and system feedback delays
- **UI/UX Verification** — Evaluated modal behaviors and dynamic UI updates (Side Cart)
- **Regression Testing** — Verified core flows remained stable throughout

---

## 📊 Test Suite Summary

| Module | Total TCs | ✅ PASS | ❌ FAIL |
|---|---|---|---|
| Home Page | 9 | 9 | 0 |
| Login Page | 6 | 5 | 1 |
| Shopping Cart | 3 | 3 | 0 |
| Details Page | 1 | 1 | 0 |
| Shopping Page | 7 | 7 | 0 |
| Favorites Page | 1 | 0 | 1 |
| **TOTAL** | **27** | **25** | **2** |

**Overall Pass Rate: 92.6%** ✅

---

## 🚨 Bug Reports

### BUG_001 — No validation error on empty login submission
| Field | Details |
|---|---|
| **Severity** | 🔴 High |
| **Priority** | 🔴 High |
| **Status** | New |
| **Reference** | TC_011 |
| **Environment** | us.shein.com — Chrome / Windows 11 Pro |

**Steps to Reproduce:**
1. Go to `us.shein.com` and click the user icon in the Navbar
2. Leave the "Mobile number or email address" field **empty**
3. Click the **"CONTINUE"** button

**Expected:** Validation error — *"Please enter a valid email or mobile number"*  
**Actual:** No error message or any reaction is displayed ❌

---

### BUG_002 — Favorites counter doesn't update in real-time
| Field | Details |
|---|---|
| **Severity** | 🟡 Low |
| **Priority** | 🟠 Medium |
| **Status** | New |
| **Reference** | TC_027 |
| **Environment** | us.shein.com — Product Detail Page — Chrome / Windows 11 Pro |

**Steps to Reproduce:**
1. Go to any Product Detail Page
2. Click the Heart icon to add the item to Favorites
3. Observe the Favorites counter in the top Navbar
4. Refresh the page or navigate to another page

**Expected:** Favorites counter increases by +1 immediately  
**Actual:** Counter only updates after a page refresh ❌

---

## 📂 Documentation & Deliverables

- ✅ **27 Test Cases** — with detailed steps, expected results, and execution status
- ✅ **2 Bug Reports** — with severity, steps to reproduce, and status
- ✅ **Test Suite Summary** — module-level pass/fail breakdown
- 📊 **[Full Test Case Document (Google Sheets)](https://docs.google.com/spreadsheets/d/1bvJPjJtGll3X6f5q3g1TiV9gOxZ44PgYSum5sPx8NGI/edit?usp=sharing)**

---

## 👩‍💻 About the QA Engineer

| | |
|---|---|
| **Name** | Gültekin Əzizova |
| **Focus** | Manual QA Testing |
| **Email** | [gultkinzizova93@gmail.com](mailto:gultkinzizova93@gmail.com) |
| **LinkedIn** | [Gültekin Əzizova](https://www.linkedin.com/in/g%C3%BClt%C9%99kin-%C9%99zizova-a71499272/) |

---

> *This project was completed as part of a QA portfolio to demonstrate professional manual testing skills including test case design, bug reporting, and systematic quality assurance.*
