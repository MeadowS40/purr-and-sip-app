# Purr & Sip Cat Cafe - Mobile App Project

## Project Overview

**Purr & Sip** is a mobile application designed for a local cat cafe to streamline booking management, reduce customer wait times, and optimize revenue during slow periods. The app provides customers with real-time availability, secure booking, and special incentives for off-peak visits while giving staff an efficient tool to manage capacity.

This project is being developed as part of a course on innovation and cloud-based application development.

---

## Project Description

The Purr & Sip Cat Cafe is a popular local establishment where customers enjoy beverages and pastries while interacting with resident cats. Due to the popularity of the cafe and strict capacity limits to ensure animal welfare, the business struggles with:

- Long customer wait times
- Manual, error-prone booking processes
- Underutilized slow periods

The Purr & Sip app solves these problems by providing a simple, intuitive mobile application that allows customers to view real-time availability, book time slots, and receive promotional offers for off-peak hours. Staff can easily manage bookings through a streamlined interface.

---

## Problem Addressing

| Problem | How the App Addresses It |
|--------|--------------------------|
| Overcrowding & Long Waits | Real-time booking system guarantees customers a spot before arrival, eliminating walk-in uncertainty |
| Inefficient Booking Process | Automated online booking with instant confirmation replaces manual phone calls and web forms |
| Underutilized Slow Periods | "Slow-Time Specials" feature offers discounts/promotions for bookings during off-peak hours, smoothing customer flow and increasing revenue |
| Cat Welfare Concerns | Controlled booking limits ensure the cafe never exceeds safe capacity for the cats |

---

## Platform

**Target Platform:** Mobile (iOS and Android)

---

## Frontend & Backend Support

### Frontend
- **Framework:** React Native
- **State Management:** React Context API or Redux Toolkit
- **UI Components:** React Native Paper (Material Design components for clean, professional UI)
- **Key Screens:**
  - User Authentication (Login/Sign Up)
  - Home/Dashboard
  - Booking Calendar
  - Booking Confirmation
  - User Profile
  - Staff View (separate interface)

### Backend
- **Backend-as-a-Service:** Google Firebase
  - **Firebase Authentication:** Handles user sign-up, login, and secure session management
  - **Cloud Firestore:** NoSQL real-time database for storing bookings, user profiles, and cafe settings
  - **Firebase Cloud Functions:** Serverless functions to automate promotional logic (e.g., applying "Slow-Time Specials")
  - **Firebase Hosting:** Optional for hosting any admin web interface

**Rationale:** Firebase provides an integrated suite of tools that work seamlessly together. Its real-time capabilities are essential for accurate booking availability, and the serverless functions simplify backend logic without requiring server management.

---

## Functionality

### User Stories

**As a Customer, I want to:**
1. Create an account and log in securely
2. View a calendar of available 90-minute time slots
3. Book a time slot and pay the reservation fee
4. Receive an instant confirmation with booking details
5. View my upcoming and past bookings
6. See special offers for off-peak time slots

---

## Design (Wireframes)

The app will follow a clean, warm aesthetic that reflects the cozy atmosphere of a cat cafe.

### Wireframe Structure
# purr-and-sip-app
Mobile app for Cat Cafe booking management - Course Project
