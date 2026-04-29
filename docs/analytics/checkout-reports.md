# Checkout Reports

Comprehensive reporting on payment and order performance.

## Overview

Checkout Reports provides detailed insights into your sales and payment processing with detailed order analytics.

## FLIK Checkout Analytics Dashboard

![Laporan & Analisis FLIK Checkout](../../assets/screenshots/Laporan%20&%20Analisis%20-%20FLIK%20Checkout/Laporan%20&%20Analisis%20FLIK%20Checkout.png)

### Summary Metrics

The dashboard displays key metrics at the top:

- **Tahun ini (2026)**: Current year filter indicator
- **Jumlah Order**: Total order count (e.g., 27)
- **Order Berhasil**: Successful orders amount in Rp (e.g., Rp17.001)
- **Potensi Penjualan**: Potential sales amount in Rp (e.g., Rp401)
- **Refund**: Refund amount in Rp (e.g., Rp0)

### Search Section

#### Search Bar
- **Search field**: "Cari External Order ID atau AWB" (Search by External Order ID or AWB)
- Search icon to find specific orders

#### Filter Dropdowns
- **Status**: Filter by order status (Completed, Processed, Rejected, etc.)
- **Kurir**: Filter by courier
- **Pembayaran**: Filter by payment method
- **Kasir**: Filter by cashier

#### Action Button
- **Export**: Button to export report data

### Orders Table

#### Table Columns
- **Order ID**: Internal order identifier (e.g., 02042026-MRMJXK-1)
- **External Order ID**: Third-party order reference (e.g., #1232, #1231, #1230)
- **Status**: Order status with colored badges:
  - **Completed** (Green badge)
  - **Processed** (Yellow badge)
  - **Rejected** (Red badge)
- **Tanggal Pesanan**: Order date and time (e.g., 2026/04/02 14:51)
- **Nama Kasir**: Cashier name (shows "-" if none)
- **Sumber**: Order source (Invoice, Checkout)
- **Nama Shopper**: Customer name (e.g., raam, Rimantoro)

### Example Orders

**Order 1: 02042026-MRMJXK-1**
- External Order ID: -
- Status: Completed
- Date: 2026/04/02 14:51
- Cashier: -
- Source: Invoice
- Shopper: raam

**Order 2: 05032026-HKLZEC-1**
- External Order ID: #1232
- Status: Processed
- Date: 2026/03/05 15:04
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 3: 05032026-OEBAUE-1**
- External Order ID: #1231
- Status: Rejected
- Date: 2026/03/05 15:01
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 4: 02032026-MQSMJG-1**
- External Order ID: #1230
- Status: Rejected
- Date: 2026/03/02 15:05
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 5: 02032026-UFPLMJ-1**
- External Order ID: #1229
- Status: Rejected
- Date: 2026/03/02 14:45
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 6: 13022026-IFXOYD-1**
- External Order ID: #1228
- Status: Completed
- Date: 2026/02/13 05:28
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 7: 11022026-NSVSSW-1**
- External Order ID: #1227
- Status: Completed
- Date: 2026/02/11 20:46
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 8: 10022026-LBXDDR-1**
- External Order ID: #1226
- Status: Completed
- Date: 2026/02/10 05:32
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

**Order 9: 10022026-BOHQIP-1**
- External Order ID: #1225
- Status: Completed
- Date: 2026/02/10 05:24
- Cashier: -
- Source: Checkout
- Shopper: Rimantoro

## How to Use

### View Checkout Reports
1. Navigate to **Laporan & Analisis** > **FLIK Checkout** from the left menu
2. View summary metrics for the current year
3. Browse orders in the table

### Search Orders
1. Use the search bar to find by External Order ID or AWB
2. Enter the ID and press search icon

### Filter Orders
1. Click **Status** dropdown to filter by order status
2. Click **Kurir** dropdown to filter by courier
3. Click **Pembayaran** dropdown to filter by payment method
4. Click **Kasir** dropdown to filter by cashier
5. Multiple filters can be applied simultaneously

### Export Data
1. Click **Export** button to export the report data
2. Select desired format and confirm

## Order Status

- **Completed**: Order successfully completed
- **Processed**: Order has been processed
- **Rejected**: Order was rejected

## Next Steps

- Back to [Analytics Overview](.)
- View [FLIK Shipping Reports](./shipping-reports.md)
