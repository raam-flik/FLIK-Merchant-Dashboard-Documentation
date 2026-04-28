# Merchant Cash Advance

Access business funding through FLIK's Merchant Cash Advance (MCA) program. The MCA Credit Engine provides automated onboarding, assessment, and fund disbursement for qualified merchants.

## Overview

Merchant Cash Advance (MCA) is FLIK's bulk purchase program that offers financing solutions for business growth. The system features:
- **Automated 5-step onboarding wizard** for merchants
- **Real-time credit assessment** and approval routing
- **Save & Resume** capability across sessions
- **Multi-stage internal approval workflow** for assessment and disbursement

## Program Objective

The MCA Credit Engine automates merchant registration through a streamlined digital workflow, replacing manual coordination between Sales, Legal, and Executive teams. It provides:
- Faster onboarding and approval times
- Centralized tracking and visibility
- Robust credit allocation and usage management

## Merchant Entry Points

There are 4 types of merchant entry scenarios:

1. **New Merchant (No Account)**: Via referral link → Account Registration → Funding Request
2. **New Merchant (Unfinished)**: Via login → Resume from last uncompleted step
3. **Existing Merchant (New to MCA)**: Via Bulk Purchase menu → MCA Introduction Page → Options to ask sales or apply
4. **Existing Merchant (Active MCA)**: Via Bulk Purchase menu → Bulk Purchase List → Apply for new funding

## MCA List Page

![List of Merchant Cash Advance](../../assets/screenshots/Merchant%20Cash%20Advance/List%20Of%20Merchant%20Cash%20Advance.png)

### Page Features

#### Search
- **Search field**: "Cari nama project" (Search project name)
- Search for specific MCA projects by project name/ID

#### Action Button
- **Ajukan Pendanaan** (Apply for Funding): Start a new MCA application

### Table Columns

The table displays all your MCA projects with the following columns:

- **Project**: Project/MCA reference number (e.g., MCA1192011910)
- **Status**: Current status of the MCA project:
  - **Live** (Blue badge) - Active funding
  - **Registrasi Belum Selesai** (Yellow badge) - Registration not yet complete
  - **Sedang Dalam Peninjauan** (Red badge) - Under review by FLIK team
- **Pendanaan** (Funding Amount): Total funding approved (e.g., Rp350.000.000)
- **Yang Perlu Dibayar** (Amount to Pay): Outstanding amount still to be paid

### Example Data

**Project 1: MCA1192011910**
- Status: Live
- Pendanaan: Rp350.000.000
- Yang Perlu Dibayar: Rp14.320.000

**Project 2: MCA1192011911**
- Status: Registrasi Belum Selesai
- Pendanaan: -
- Yang Perlu Dibayar: -

**Project 3: MCA1192011910**
- Status: Sedang Dalam Peninjauan
- Pendanaan: -
- Yang Perlu Dibayar: -

### Pagination

- Shows 1-10 of 1000 records
- Navigation: Previous, page numbers (1, 2, 3, ..., 100), Next

## MCA Detail Page

![Detail of Merchant Cash Advance](../../assets/screenshots/Merchant%20Cash%20Advance/Detail%20of%20Merchant%20Cash%20Advance.png)

### Summary Information

Four key financial metrics displayed at the top:

- **Pendanaan** (Funding): Total amount of approved funding (e.g., Rp125.000.000)
- **Yang Perlu Dibayar** (Amount to Pay): Remaining payment obligation (e.g., Rp140.000.000)
- **Sisa Pembayaran** (Payment Remaining): Outstanding balance (e.g., Rp95.300.000)
- **Periode** (Period): Duration remaining (e.g., 36 Hari lagi - 36 Days remaining)

### Payment History

#### Search & Filter
- **Search field**: "Cari reference" (Search payment reference)
- Filter and export payment transaction data

#### Table Columns

- **Tanggal Pembelian** (Purchase Date): Transaction date and time (e.g., Dec 7, 2019 23:26)
- **Amount**: Payment amount (e.g., Rp290.000.000)
- **Reference**: Reference number for the transaction (e.g., 05122024-JDSKEL-1)

#### Payment Records
Complete history of all payment transactions with dates, amounts, and references for verification and reconciliation.

## MCA Onboarding Journey (5-Step Flow)

The MCA application process is a 5-step self-service wizard designed with "Save & Resume" capabilities:

### Step 0: Account Registration (Entry Point)

![Step 0](../../assets/screenshots/Merchant%20Cash%20Advance/1.png)

- **Nama Merchant**: Official business name
- **Nama Lengkap**: Full name of director/PIC
- **Pendapatan per Bulan**: Monthly revenue bracket (used to show potential funding)
- **Nomor WhatsApp**: Primary contact for updates
- **Email**: Login username and official notices
- **Password**: Secure credentials
- **Terms & Conditions**: Must accept FLIK policies

### Step 1: Funding Request

![Step 1](../../assets/screenshots/Merchant%20Cash%20Advance/2.png)

- **Tipe Bisnis**: Personal or Perusahaan (Company)
- **Alamat Perusahaan**: Business location details
- **Requested Amount (IDR)**: Total funding sought
- **Requested Tenor (Days)**: Desired repayment duration
- **Business Age**: Years of operation
- **Est. Gross Margin (%)**: Self-reported profitability margin
- **Potential Funding**: Calculated TBC (To Be Confirmed)
- **Save & Exit**: Can save draft to consult stakeholders

### Step 2: Identity Verification

![Step 2](../../assets/screenshots/Merchant%20Cash%20Advance/3.png)

- **NIK Direktur**: Director's national ID number (16 digits)
- **KTP Direktur**: Director's ID card image (JPG, JPEG, PNG | Max 5MB)
- **NPWP Direktur**: Tax ID image (hidden if Personal business type)
- **NIK Owner** (Optional): Business owner's ID number
- **KTP Owner** (Optional): Business owner's ID card image
- **Automated KYC Check**: System validates NIK against KTP OCR and FLIK account data

### Step 3: Channel Integration & Revenue Validation

![Step 3](../../assets/screenshots/Merchant%20Cash%20Advance/5.png)

Merchants can connect revenue sources through two integration paths:

#### Path A: Automated Binding (Direct OAuth)
Available channels:
- **Marketplace & Delivery**: FORSTOK, GoFood, GrabFood, ShopeeFood, Tokopedia, Shopee, TikTok Shop, Lazada, Blibli, Shopify, WooCommerce, Magento
- **Offline & POS**: Offline Store, Moka POS, Majoo, Pawoon, Olsera, iReap POS
- **Accounting & Finance**: Zahir Accounting, Jurnal by Mekari, Accurate Online, Kledo, Xero, QuickBooks

Click "Hubungkan Dengan [Platform Name]" to authorize FLIK and automatically retrieve transaction data.

#### Path B: Manual Entry
For each channel type, upload:
- Store/business name
- Store URL or address
- Revenue file (last 6 months) - PDF, Max 10MB
- Screenshot of revenue report - JPG, JPEG, PNG | Max 5MB

#### Marketing Channels (Manual Only)
- Account name and ID
- Currency (IDR, USD, etc.)
- Data period
- Total ad spend (6 months)
- Number of active campaigns
- Days ads were active
- Average monthly ad spend
- Ad report files

### Step 4: Legal Documents

![Step 4](../../assets/screenshots/Merchant%20Cash%20Advance/6.png)

- **NPWP PT / Pribadi**: Tax ID number
- **NPWP Upload**: Tax ID image (PDF | Max 10MB)
- **AKTA**: Corporate deed and amendments (PDF | Max 10MB)
- **SK Kemenkumham**: Ministry approval (PDF | Max 10MB)
- **NIB**: Business Identification Number (PDF | Max 10MB)

### Step 5: Financial Documents

![Step 5](../../assets/screenshots/Merchant%20Cash%20Advance/7.png)

- **Bank Statement**: Last 6 months of official bank records (PDF | Max 10MB)
- **Disbursement Details**:
  - Bank name selection
  - Account number
  - Account name (must match bank statement)
- **Debt Information** (Optional): 
  - Provider, maturity date, and amount of existing liabilities
  - Ability to add multiple debt entries
- **Laporan Laba Rugi (P&L)**: Previous month statement (PDF | Max 10MB)
- **Neraca Keuangan (Balance Sheet)**: Previous month statement (PDF | Max 10MB)
- **T&C Submission**: Accept "Setujui Syarat & Ketentuan CLIK" to complete submission

### Submission & Redirection Logic
- **First-Time Request**: Redirected to Waiting Page for review
- **Repeat Request**: Redirected to Bulk Purchase List page

## Project Statuses

### Application Statuses
- **Pending Registration**: Merchant started but not submitted
- **In Review**: Application submitted and under assessment
- **Need Reupload**: Sales team flagged incorrect/missing documents
- **Ready to Disburse**: PKS (legal agreement) uploaded, funds ready for release

## File Upload Requirements

### Standard File Constraints
- **Images** (KTP, Screenshots): JPG, JPEG, PNG | Max 5MB per file
- **Documents** (Legal, Financial): PDF | Max 10MB per file

## How to Use

### View Your MCA Projects
1. Navigate to **Pendanaan** > **Merchant Cash Advance**
2. See list of all your MCA projects
3. View current status, funding amounts, and payment obligations
4. Use search to find specific projects
5. Click pagination to see more projects

### Apply for New Funding
1. Click **Ajukan Pendanaan** button
2. Complete the 5-step onboarding process
3. Submit application with required documents
4. Monitor progress in Bulk Purchase List

### View Payment Details
1. Click on an MCA project from the list
2. Review funding summary metrics at top
3. Search payment history by reference
4. Export data for records

## Key Features

- **Asynchronous Onboarding**: Save progress and resume anytime
- **Automated Assessment**: Credit scoring based on revenue and business metrics
- **Multi-stage Approval**: Sales, Risk assessment, and CEO approval routing
- **Real-time Visibility**: Track application status through the dashboard
- **Flexible Repayment**: Daily deduction based on sales-based holdback model

## Next Steps

- Back to [Financial Overview](.)
- View [Saldo (Balance)](./saldo.md)
