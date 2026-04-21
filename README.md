# FLIK Merchant Dashboard Documentation

Welcome to the official documentation for the FLIK Merchant Dashboard. This comprehensive guide covers all features, modules, and workflows for merchants using the FLIK platform.

## Overview

The FLIK Merchant Dashboard is a comprehensive platform designed to help merchants manage their business operations efficiently. It includes features for checkout management, shipping logistics, promotions, marketing, analytics, and financial management.

## Platform

- **Web Platform** (Desktop & Responsive)

## Core Modules

### 1. **Authentication & Access**
Entry point for merchants to register or login into the dashboard.

- [Login & Registration](./docs/authentication.md)
- Account creation and password management
- User authentication flow
- Password recovery

### 2. **Dashboard & Settings**
Main dashboard and general settings for store management.

- [Dashboard Overview](./docs/dashboard.md)
- [Profile Management](./docs/profile.md)
- [General Settings](./docs/general-settings.md)

### 3. **Saldo (Account Balance)**
Manage account balance and financial transactions.

- [Saldo Management](./docs/financial/saldo.md)
- View transaction history
- Manage payment methods
- Purchase service credits

### 4. **FLIK Checkout**
Core payment and order management features for online transactions.

- [Invoice Management](./docs/flik-checkout/invoice.md)
- [Order Form Builder](./docs/flik-checkout/order-form.md)
- [Toko Offline (Point of Sale)](./docs/flik-checkout/toko-offline.md)
- [Checkout Personalization](./docs/flik-checkout/checkout-personalization.md)

### 5. **FLIK Shipping**
Comprehensive logistics and shipping management system.

- [Pengiriman (Single Warehouse Shipping)](./docs/flik-shipping/pengiriman.md)
- [Multiple Warehouse Shipping](./docs/flik-shipping/multiple-warehouse.md)
- [Lacak Pengiriman (Shipment Tracking)](./docs/flik-shipping/lacak-pengiriman.md)
- [Cek Red Zone (Check Red Zone)](./docs/flik-shipping/cek-red-zone.md)
- [Pengaturan Pengiriman (Shipping Settings)](./docs/flik-shipping/pengaturan-pengiriman.md)

### 6. **Pendanaan (Funding)**
Business funding and financing options.

- [Merchant Cash Advance](./docs/financial/merchant-cash-advance.md)
  - Apply for business funding
  - Track funding status
  - Manage repayment

### 7. **Marketing**
Customer relationship and marketing management tools.

- [Customer Management](./docs/marketing/customer.md)
  - Manage customer database
  - Track purchase history
  - Customer segmentation
- [Leads Management](./docs/marketing/leads-management.md)
  - Capture and qualify leads
  - Sales pipeline tracking
  - Lead scoring

### 8. **Promosi (Promotions)**
Create and manage promotional campaigns to drive sales.

- [Voucher](./docs/promotions/voucher.md)
  - Create discount codes
  - Track redemption
  - Campaign analytics
- [Post Purchase Offer](./docs/promotions/post-purchase-offer.md)
  - Encourage repeat purchases
  - Time-limited offers
  - Conversion tracking
- [Cashback](./docs/promotions/cashback.md)
  - Loyalty reward programs
  - Set reward rates
  - Track payouts
- [QR Campaign](./docs/promotions/qr-campaign.md)
  - Create QR codes
  - Track engagement
  - Measure conversions

### 9. **Analytics & Reporting**
Performance tracking and business intelligence.

- [FLIK Checkout Reports](./docs/analytics/checkout-reports.md)
  - Sales analytics
  - Order tracking
  - Payment metrics
  - Revenue analysis
- [FLIK Shipping Reports](./docs/analytics/shipping-reports.md)
  - Shipment metrics
  - Carrier performance
  - Delivery success rates
  - Cost analysis

## Quick Start Guide

### Step 1: Login to Dashboard
1. Navigate to the Login page
2. Enter your credentials
3. Access the main dashboard

### Step 2: Explore Modules
- Visit each module from the main navigation
- Familiarize yourself with available features

### Step 3: Set Up Your Store
- Configure settings in Profile & General Settings
- Set up shipping preferences
- Customize checkout experience

## Features by Category

### E-Commerce Features
- Create and manage invoices
- Build custom order forms
- Manage offline store (POS system)
- Personalize checkout experience
- Track orders and shipments

### Logistics Features
- Manage shipments from single/multiple warehouses
- Check red zones for delivery areas
- Track package delivery status
- Configure shipping settings
- Multiple shipping step workflows

### Marketing Features
- Create voucher campaigns
- Set up cashback promotions
- Generate QR campaigns
- Post-purchase offer management
- Customer segmentation
- Lead management system

### Financial Features
- Apply for merchant cash advance
- View and manage account balance
- Purchase credit for services

### Analytics Features
- View checkout performance metrics
- Analyze shipping operations
- Track campaign effectiveness

## Documentation Structure

```
/docs
├── authentication.md                  # 1. Login & Registration
├── dashboard.md                       # 2. Dashboard Overview
├── profile.md                         # 2. Profile Management
├── general-settings.md                # 2. General Settings
├── financial/
│   └── saldo.md                      # 3. Account Balance Management
├── flik-checkout/
│   ├── README.md                     # 4. FLIK Checkout Overview
│   ├── invoice.md                    # 4. Invoice Management
│   ├── order-form.md                 # 4. Order Form Builder
│   ├── toko-offline.md               # 4. POS System
│   └── checkout-personalization.md   # 4. Checkout Customization
├── flik-shipping/
│   ├── README.md                     # 5. FLIK Shipping Overview
│   ├── pengiriman.md                 # 5. Single Warehouse Shipping
│   ├── multiple-warehouse.md          # 5. Multi-warehouse Shipping
│   ├── lacak-pengiriman.md           # 5. Shipment Tracking
│   ├── cek-red-zone.md               # 5. Red Zone Checking
│   └── pengaturan-pengiriman.md      # 5. Shipping Settings
├── financial/
│   └── merchant-cash-advance.md      # 6. Pendanaan / MCA
├── marketing/
│   ├── README.md                     # 7. Marketing Overview
│   ├── customer.md                   # 7. Customer Management
│   └── leads-management.md           # 7. Leads Management
├── promotions/
│   ├── README.md                     # 8. Promotions Overview
│   ├── voucher.md                    # 8. Voucher Campaigns
│   ├── post-purchase-offer.md        # 8. Post-Purchase Offers
│   ├── cashback.md                   # 8. Cashback Programs
│   └── qr-campaign.md                # 8. QR Campaigns
└── analytics/
    ├── README.md                     # 9. Analytics Overview
    ├── checkout-reports.md           # 9. Checkout Reports
    └── shipping-reports.md           # 9. Shipping Reports
```

## Screenshots

All UI screenshots are organized by module in the `/assets/screenshots/` directory for reference during implementation or usage.

## Need Help?

- Click the **gear icon** in the top bar for settings
- Click the **question mark** for help and FAQ
- Access **Produk Kami** (Our Products) for information about available services
- Use the **Beli Kredit** (Buy Credit) option to purchase service credits
- Visit your **Profile** for account settings

## Version

**Current Version**: 1.0.0

## Last Updated

April 21, 2026

---

For more information, please visit our official website or contact support.
