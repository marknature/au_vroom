# 🚐 AU VROOM — *Don’t Wait, Just Vroom*

AU VROOM is a **full-stack, mobile-first campus transportation platform** designed to modernize shuttle services at Africa University.
It combines **real-time shuttle tracking, seat booking, on-demand rides, and digital payments** into one seamless student-centered experience.

AU VROOM is built **from scratch**, using a production-grade architecture inspired by modern ride-hailing platforms (Uber-style systems), but **reimagined specifically for campus mobility**.



## 🎯 Problem Statement

Campus transport systems often suffer from:

* Uncertainty around shuttle arrival times
* Overcrowding and missed rides
* Lack of real-time visibility
* No structured data for planning and optimization

**AU VROOM solves this by turning campus transport into a smart, trackable, and bookable service.**



## 🚀 What AU VROOM Is

AU VROOM is **not just a shuttle tracker**.
It is a **full-stack transport management system** with:

* Live GPS-based vehicle tracking
* Fixed-route shuttle monitoring
* On-demand ride requests (Flexi drivers)
* Seat booking & availability control
* Secure authentication
* Integrated digital payments
* Admin analytics & fleet oversight



## 🧭 Phase 0 — Planning & System Design

This phase defines **roles, features, flows, and transport logic** before implementation.



## 👥 User Roles & Core Features

### 🎓 Students & Staff (Riders)

* View **live shuttle locations** on a map
* See **estimated arrival times (ETA)** for selected stops
* Choose a **campus stop** from a predefined list
* **Book a seat in advance** on fixed routes
* Request **on-demand rides** if flexi-drivers are available
* Receive **push notifications** when the shuttle is near their stop



### 🚗 Drivers

* Secure authentication under a driver profile
* Toggle **availability (Online / Offline)**
* View:

  * Assigned fixed routes
  * Incoming on-demand ride requests
* Share **live GPS location** with riders and admin
* Start and end trips to log:

  * Service hours
  * Route coverage
  * Demand patterns



### 🛠️ Admin (Operations Team)

* Add, edit, or remove **stops and shuttle routes**
* Monitor **all vehicles and drivers live** via dashboard
* Manage driver assignments
* Analyze **usage reports and demand trends**
* Use insights to optimize transport schedules



## 🚌 Stops & Virtual Bus Stops

### Rider Interaction Models

**Scenario A (Chosen Approach – Phase 1)**

* Rider selects a campus stop
* App displays ETA (e.g. *“Main Gate — 10 mins”*)

**Scenario B**

* GPS auto-detects nearest stop

**Scenario C**

* Manual stop selection + GPS fallback

✅ **Why Scenario A?**
It is simpler, more reliable, and faster to implement while still delivering high value.



## 🖼️ App Wireframe Overview

### 📱 Rider App

* Live Map View

  * Shuttle pins
  * Stop markers
  * ETA badges
* Booking Actions

  * Book seat (fixed drivers)
  * Request ride (flexi drivers)
* Booking Confirmation Screen

  * Driver details
  * Arrival countdown



### 📲 Driver App

* Login Screen
* Home Dashboard

  * Availability toggle
  * Active route view
* Live Map

  * Routes & pickup points
* Trip Controls

  * Start Trip
  * End Trip
* On-demand Requests

  * Accept / Reject



### 🖥️ Admin Dashboard

* Live fleet tracking map
* Driver management panel
* Stop & route editor
* Analytics & reports



## 🚦 Driver Models

### 🔄 Flexi Drivers (On-Demand)

* Operate similar to Uber drivers
* Accept ride requests anytime
* Serve students outside fixed schedules



### ⏱️ Fixed Route Drivers

* Assigned predefined routes & timetables
* Run every **30–60 minutes**
* Students can track and book seats



## 🧠 Technical Foundation

AU VROOM is architected using **modern full-stack mobile development principles**, inspired by enterprise-grade ride-hailing systems.

### Core Stack

* **Frontend:** React Native + Expo
* **Language:** TypeScript (end-to-end type safety)
* **Styling:** NativeWind (Tailwind CSS for React Native)
* **State Management:** Zustand
* **Backend:** Expo API Routes
* **Database:** Serverless PostgreSQL (Neon)
* **Authentication:** Clerk (Email + OAuth)
* **Maps & Location:** Google Maps Platform
* **Payments:** Stripe
* **Notifications:** Push Notifications



## 💳 Payments & Monetization

* Secure Stripe payment integration
* Seat-based or ride-based payments
* Payment confirmation & success flow
* Foundation for future:

  * Subscription plans
  * Semester transport passes



## 📈 Future Roadmap

* AI-based demand prediction
* Shuttle capacity optimization
* QR-code boarding verification
* Accessibility-aware routing
* University system integration
* Admin forecasting dashboards


🚐💨
