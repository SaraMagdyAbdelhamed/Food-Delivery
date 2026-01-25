Multi-Vendor Food Delivery Platform
🚀 Project Overview
Food Delivery Platform is a comprehensive multi-vendor food delivery ecosystem inspired by industry leaders like Talabat and Elmenus. The platform facilitates a seamless connection between hungry customers, a diverse range of local restaurants (vendors), and a reliable delivery network.

Built with a robust Laravel API and a high-performance Frontend (Next.js/Vue.js), Laffa is engineered for scalability, real-time tracking, and secure financial transactions through an integrated wallet system.

🏗️ High-Level Features
Customer Identity & Auth: Secure gateway with OTP and social integration.

Multi-Vendor Marketplace: Comprehensive restaurant discovery and menu browsing.

Intelligent Cart System: Single-vendor enforcement and dynamic calculations.

Order Lifecycle Management: Real-time processing from "Pending" to "Delivered."

Wallet & Payments: A closed-loop financial system with gateway integrations.

Live Tracking: Real-time movement updates via WebSockets.

Management Dashboards: Dedicated interfaces for Vendors and System Admins.

🛠️ Detailed Functional Requirements
1. User Registration & Authentication
Registration: Account creation with phone number validation.

OTP Integration: Secure 2FA/Verification via Twilio Verify API.

Social Auth: Quick login via Google, Apple, or Facebook.

Forget Password: OTP-based recovery and secure reset.

Session Management: Token-based authentication (Sanctum/Passport).

2. Profile Management
Personal Info: Edit name, profile picture, and contact details.

Address Book: Manage multiple addresses (Home, Work, Other) with GPS pinning.

Order History: View detailed past orders with "One-Tap Reorder."

Favorites: Save preferred restaurants and specific meals.

3. Restaurant & Menu Management
Vendor Onboarding: Application and approval workflow for new restaurants.

Menu Builder: Create categories (Appetizers, Mains) and add food items.

Advanced Add-ons: Manage variants (Sizes), optional toppings, and required choices.

Status Control: Manual and scheduled "Open/Closed" toggles.

Inventory Management: Quick "Out of Stock" toggle for individual items.

4. Cart Management
Vendor Lock Logic: Ensures items are only added from one vendor at a time.

Item Customization: Modify add-ons and special instructions within the cart.

Quantity Control: Real-time subtotal updates on quantity change.

Cart Persistence: Cart remains synced across different user devices.

5. Order Management
Workflow Engine: Moves orders through statuses (Accepted → Preparing → Out for Delivery).

Cancellation Policy: Automated logic for cancellations and wallet refunds.

Real-time Updates: Push notifications and in-app alerts via Pusher/Reverb.

Live Tracking: Google Maps integration for driver location.

6. Wallet & Payment Integration
Top-up: Add balance via Credit Card, Debit Card, or local providers (Fawry/Paymob).

Wallet Checkout: Seamless payment using stored balance.

Transaction History: Detailed logs of all credits, debits, and refunds.

COD Management: Support for Cash on Delivery with driver reconciliation.

7. Offers & Promotions
Promo Codes: Percentage and fixed discounts with usage limits.

Restaurant Deals: Specific meal-based offers (e.g., Buy 1 Get 1).

Campaign Banners: Targeted homepage banners for seasonal promotions.

8. Dashboards & Analytics
System Admin: Global sales overview, vendor approval, and commission settings.

Vendor Portal: Daily revenue reports, top-selling items, and customer reviews.

Driver App: Task queue, earnings per trip, and optimized routing.
