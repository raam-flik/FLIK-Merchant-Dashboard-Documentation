# QR Campaign

Create QR code-based marketing campaigns for easy promotion sharing and tracking.

## Overview

QR Campaign allows you to generate trackable QR codes linked to promotions, with detailed scan and claim metrics.

## QR Campaign List Page

![List of QR Campaign](../../assets/screenshots/Promosi%20-%20QR%20Campaign/List%20of%20QR%20Campaign.png)

### Search Section

#### Search Bar
- **Search field**: "Cari QR Campaign" (Search QR Campaign by name)
- Search icon to find specific campaigns

#### Filter Dropdowns
- **Status**: Filter by campaign status (Aktif/Tidak Aktif)
- **Marketplace**: Filter by marketplace (Tokopedia, Shopee, etc.)

#### Action Button
- **Buat QR Campaign** (Create QR Campaign): Button to create new QR campaign

### QR Campaign Table

#### Table Columns
- **QR ID**: Unique identifier for each QR campaign
- **Marketplace**: Associated marketplace (e.g., Tokopedia, Shopee)
- **Status**: Campaign status with toggle (Aktif/Tidak Aktif)
- **Scan Count**: Total number of QR code scans
- **Successful Claims**: Number of successful claims from scans
- **Created At**: Campaign creation date and time
- **Action**: 
  - **Print** button to print the QR campaign
  - **Detail** button to view campaign details
  - **Hapus** (Delete) button to delete the campaign

### Example QR Campaigns

**Campaign 1: QR--032bf5a3-399e-4df5-a025...**
- Marketplace: Tokopedia
- Status: Aktif
- Scan Count: 4
- Successful Claims: 2
- Created At: 11 Mar 2026 16:53

**Campaign 2: QR--032bf5a3-399e-4df5-a025...**
- Marketplace: Shopee
- Status: Aktif
- Scan Count: 3
- Successful Claims: 2
- Created At: 11 Mar 2026 16:39

### Pagination
- Showing 1-2 of 2 records
- Navigation: Prev, 1, Next

## Create QR Campaign Page

![Create QR Campaign](../../assets/screenshots/Promosi%20-%20QR%20Campaign/Create%20QR%20Campaign.png)

### QR Campaign Form Fields

#### Marketplace Selection
- **Marketplace** (Required): Dropdown field with placeholder "Pilih Marketplace" (Select Marketplace)

#### Campaign Status
- **Status** (Required): Dropdown field set to "Aktif" (Active)

#### Information Note
- **Note**: "Jumlah reward yang diberikan (dalam Rp) diatur di halaman Menu Promosi -> Cashback"
  - Translation: The reward amount (in Rp) is configured in Menu Promosi -> Cashback

### Action Button
- **Buat QR Campaign** (Create QR Campaign): Button to create the QR campaign

## How to Use

### Create New QR Campaign
1. Click **Buat QR Campaign** button on List page
2. Select marketplace from "Pilih Marketplace" dropdown
3. Confirm status is set to "Aktif" (Active)
4. Note: Reward amounts are configured separately in Cashback settings
5. Click **Buat QR Campaign** to save

### View Campaign Details
1. Click **Detail** button next to QR campaign in list
2. View complete campaign information and metrics

### Delete QR Campaign
1. Click **Hapus** (Delete) button next to QR campaign in list
2. Confirm deletion

### Filter QR Campaigns
1. Click **Status** dropdown to filter by Aktif/Tidak Aktif
2. Click **Marketplace** dropdown to filter by specific marketplace
3. Use search bar to find by QR ID or campaign identifier

## QR Campaign Metrics

### Metrics Displayed
- **Scan Count**: Total number of times the QR code has been scanned
- **Successful Claims**: Number of successful transactions/claims resulting from QR scans

### Campaign Status

- **Aktif** (Active): QR campaign is currently running and accepting scans
- **Tidak Aktif** (Inactive): QR campaign is disabled and not accepting scans

### Campaign Actions

#### Print Action
Click the Print button to:
- Print the QR code for the campaign
- Get a printable version for offline distribution

#### Detail Action
Click the Detail button to:
- View complete QR campaign information
- Access campaign metrics and statistics
- Monitor scan data and claims

#### Hapus Action
Click the Hapus (Delete) button to:
- Permanently remove the QR campaign
- Delete all associated campaign data

## Related Settings

QR Campaign reward amounts are configured in the **Cashback** section:
- Navigate to Menu Promosi -> Cashback to set reward amounts
- Rewards are applied to QR campaigns through cashback rules

## Next Steps

- Back to [Promotions Overview](.)
- View [Voucher](./voucher.md)
- View [Cashback](./cashback.md)
- View [Post Purchase Offer](./post-purchase-offer.md)
