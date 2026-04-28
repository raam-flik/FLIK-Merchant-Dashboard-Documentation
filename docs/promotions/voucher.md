# Voucher Management

Create and manage promotional vouchers for discounts and shipping offers.

## Overview

Voucher Management allows you to create and manage discount vouchers with customizable discount types and validity dates.

## Voucher List Page

![List Voucher Page](../../assets/screenshots/Promosi%20-%20Voucher/List%20Voucher%20Page.png)

### Search and Filter Section

#### Search Bar
- **Search field**: "Cari nama voucher" (Search voucher by name)
- Search icon to find specific vouchers

#### Filter Dropdowns
- **Status**: Filter by voucher status (Aktif/Tidak Aktif)
- **Tipe Voucher**: Filter by voucher type

#### Action Button
- **Buat Voucher** (Create Voucher): Button to create new voucher

### Voucher Table

#### Table Columns
- **Nama Voucher** (Voucher Name): Name/identifier of the voucher (e.g., "SHIPDHL2V10K", "discount onkir ceria")
- **Tipe Voucher** (Voucher Type): Type of discount offered (e.g., "Diskon Pengiriman" - Shipping Discount)
- **Status**: Current status with colored badges:
  - **Aktif** (Green badge - Active)
  - **Tidak Aktif** (Gray badge - Inactive)
- **Action**: 
  - **Ubah** (Edit) button to modify voucher details

### Example Vouchers

**Voucher 1: SHIPDHL2V10K**
- Type: Diskon Pengiriman
- Status: Aktif

**Voucher 2: discount onkir ceria**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 3: diskon ongkir agt**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 4: test**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 5: Discount ongkir ceria**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 6: testingpromoaug1**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 7: Juliongkir**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

**Voucher 8: Shipping Discount Rp15.000**
- Type: Diskon Pengiriman
- Status: Tidak Aktif

### Pagination
- Showing 1-8 of 8 records
- Navigation: Prev, 1, Next

## Create Voucher Page

![Buat Voucher Page](../../assets/screenshots/Promosi%20-%20Voucher/Buat%20Voucher%20Page.png)

### Voucher Form Fields

#### Basic Information
- **Nama voucher** (Voucher Name): Text input field with placeholder "Tulis nama voucher"
- **Jumlah minimal order** (Minimum Order Amount): Number input field (default: 0)
- **Pilih tipe pengiriman** (Select Shipping Type): Dropdown menu with option "Diskon Pengiriman" (Shipping Discount)

#### Discount Information
- **Jumlah diskon tetap** (Fixed Discount Amount): Text input field
  - Helper text: "Maksimal Diskon Tetap adalah Rp400.000" (Maximum Fixed Discount is Rp400.000)

#### Active Dates Section
- **Start date**: Date picker field showing "21 April 2026"
- **Start time (WIB)**: Time input field showing "13:49" (WIB = Western Indonesia Time)
- **Set end date**: Checkbox to enable end date setting (unchecked by default)

#### Status Section
- **Status Diskon** (Discount Status): Toggle switch with two options:
  - "Tidak Aktif" (Inactive)
  - "Aktif" (Active)

#### Action Buttons
- **Kembali** (Back): Button to return to previous page
- **Buat Voucher** (Create Voucher): Button to create the voucher

## How to Use

### Create New Voucher
1. Click **Buat Voucher** button on List page
2. Fill in voucher name in "Nama voucher" field
3. Set minimum order amount in "Jumlah minimal order" field
4. Select shipping type from "Pilih tipe pengiriman" dropdown (currently "Diskon Pengiriman")
5. Enter fixed discount amount in "Jumlah diskon tetap" field (max Rp400.000)
6. Set start date and time
7. Optionally check "Set end date" to add expiration date
8. Toggle "Status Diskon" to activate or deactivate
9. Click **Buat Voucher** to save

### Edit Existing Voucher
1. Click **Ubah** (Edit) button next to voucher in list
2. Modify voucher details as needed
3. Save changes

### Filter Vouchers
1. Click **Status** dropdown to filter by Aktif/Tidak Aktif
2. Click **Tipe Voucher** dropdown to filter by type
3. Use search bar to find by voucher name

## Voucher Types

Based on visible data, vouchers can be of type:
- **Diskon Pengiriman** (Shipping Discount): Discount applied to shipping costs

## Voucher Status

- **Aktif** (Active): Voucher is currently active and can be used
- **Tidak Aktif** (Inactive): Voucher is inactive and cannot be used

## Next Steps

- Back to [Promotions Overview](.)
- View [Cashback](./cashback.md)
- View [Post Purchase Offer](./post-purchase-offer.md)
- View [QR Campaign](./qr-campaign.md)
