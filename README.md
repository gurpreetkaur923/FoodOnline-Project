# 🍽️ Django Restaurant Marketplace Platform #

A full-stack, production-style restaurant marketplace built with Django, simulating real-world platforms like food delivery and vendor aggregation systems. This project goes beyond CRUD and demonstrates scalable architecture, advanced backend logic, payment integration, and geolocation-based discovery.

# 🚀 Overview

This platform enables:

- Vendors to register and manage restaurants & menus
- Customers to browse, search, and order food
-  Admins to control approvals and platform operations

It includes real-world features such as:

- Multi-vendor system
- Dynamic cart & checkout
- Location-based search
- Payment gateway integration
- Order lifecycle management

# 🧠 Key Highlights

- 🔐 Custom authentication system with role-based access (Customer, Vendor, Admin)
- 📍 Location-aware restaurant discovery (Google Autocomplete + geolocation)
- 🛒 Dynamic cart with AJAX-powered updates
- 💳 Integrated payments (PayPal & Razorpay)
- 📦 Order lifecycle tracking with unique order numbers
- 📊 Vendor dashboards with revenue analytics
- ⏱ Dynamic business hours & tax calculation modules
- ⚡ Optimized UX with asynchronous requests (AJAX)
- 🏗️ Tech Stack

# Backend

- Django
- Django REST principles (modular apps)
- PostgreSQL

# Frontend

- HTML, CSS, JavaScript
- AJAX (for dynamic interactions)
- Responsive UI

# Other Integrations

- Google Places API (Autocomplete & geolocation)
- PayPal & Razorpay (payments)
- Email services (SMTP configuration)
  
# 🧩 Core Modules
# 👤 Authentication & Users
- Custom user model
- Registration & login system
- Token-based email verification
# Django messages & error handling
# 🏪 Vendor & Restaurant Management
- Vendor registration & approval workflow
- Restaurant profile creation with validation
- Vendor dashboard with analytics
- Business hours management (dynamic via AJAX)
# 🍔 Menu Builder
- Category CRUD system
- Food items CRUD with relationships
- Many-to-Many relationships for flexible menu design
# 🛒 Cart & Marketplace
- Add/remove/update cart items (AJAX + frontend sync)
- Real-time cart updates
- Smart search & filtering
- Marketplace listing of restaurants
# 📍 Location-Based Features
- Google Autocomplete integration
- Detect user’s current location
- Nearby restaurant discovery
- Distance-based filtering
# 💳 Orders & Payments
- Order model with structured lifecycle
- Checkout system
- Unique order number generation
- PayPal & Razorpay integration
- Post-order processing
# 📊 Dashboards & Analytics
- Customer dashboard
- Vendor dashboard
- Revenue tracking (monthly & total)
- Middleware for custom metrics
# 📧 Notifications
- Email templates integration
- Order confirmations
- Account verification emails
# ⚙️ Advanced Features
- Custom middleware
- Dynamic tax module
- Signals for automation
- Media file handling
- Fully responsive design
# 🧪 Deployment

Deployed on a Virtual Private Server (Linode) with:

- Gunicorn
- Nginx
- PostgreSQL
# Static & media file configuration
# 📸 Screenshots

(Add screenshots here to significantly boost recruiter interest)

# 🎯 What This Project Demonstrates
- Ability to design scalable Django architectures
- Handling real-world business logic
- Working with third-party APIs & payment systems
- Building multi-role platforms
- Implementing asynchronous frontend interactions
- Understanding of deployment & production environments
