# Shipping Reports

Comprehensive reporting on shipping and logistics performance.

## Overview

Shipping Reports provides detailed insights into your delivery operations and carrier performance.

## FLIK Shipping Analytics Dashboard

![Laporan & Analisis FLIK Shipping](../../assets/screenshots/Laporan%20&%20Analisis%20FLIK%20Shipping/Laporan%20&%20Analisis%20FLIK%20Shipping.png)

### Summary Metrics

The dashboard displays key metrics at the top:

- **Minggu Ini**: Current week filter indicator
- **Total Pengiriman**: Total shipments count (e.g., 1)
- **Berhasil**: Successful shipments count (e.g., 0)
- **Dikembalikan**: Returned shipments count (e.g., 0)
- **Bermasalah**: Problematic shipments count (e.g., 0)

### Search Section

#### Search Bar
- **Search field**: "Cari Order ID atau AWB" (Search by Order ID or AWB)
- Search icon to find specific shipments

#### Filter Dropdowns
- **Status**: Filter by shipment status (Menunggu Pembayaran/Waiting for Payment, etc.)
- **COD / Non COD**: Filter by payment method
- **Kurir**: Filter by courier
- **Warehouse**: Filter by warehouse location

#### Action Button
- **Export**: Button to export report data

### Shipment Table

#### Table Columns
- **Order ID**: Internal order identifier (e.g., 674A50A4)
- **AWB**: Airway bill number (tracking number)
- **Kurir**: Courier service used (e.g., JNE)
- **Layanan Kurir**: Courier service type (e.g., Regular)
- **COD/Non COD**: Payment method indicator (COD - Cash on Delivery)
- **Status**: Shipment status with colored badges:
  - **Menunggu Pembayaran** (Waiting for Payment - Blue badge)
- **Tanggal Pembuatan**: Shipment creation date and time (e.g., Apr 21, 2026 06:19)

### Example Shipment

**Shipment 1: 674A50A4**
- AWB: -
- Courier: JNE
- Service Type: Regular
- Payment: COD
- Status: Menunggu Pembayaran
- Date: Apr 21, 2026 06:19

### Pagination
- Showing 1-1 of 1 records
- Navigation: Prev, 1, Next

## How to Use

### View Shipping Reports
1. Navigate to **Laporan & Analisis** > **FLIK Shipping** from the left menu
2. View summary metrics for the current week
3. Browse shipments in the table

### Search Shipments
1. Use the search bar to find by Order ID or AWB
2. Enter the ID and press search icon

### Filter Shipments
1. Click **Status** dropdown to filter by shipment status
2. Click **COD / Non COD** dropdown to filter by payment method
3. Click **Kurir** dropdown to filter by courier
4. Click **Warehouse** dropdown to filter by warehouse location
5. Multiple filters can be applied simultaneously

### Export Data
1. Click **Export** button to export the report data
2. Select desired format and confirm

## Shipment Status

- **Menunggu Pembayaran** (Waiting for Payment): Shipment awaiting payment before processing

## Next Steps

- Back to [Analytics Overview](.)
- View [Checkout Reports](./checkout-reports.md)
