# Cashback Programs

Create and manage cashback rules to reward customer purchases.

## Overview

Cashback Programs allow you to create conditional cashback rules that reward customers based on specific purchase criteria.

## Cashback List Page

![List of Cashback](../../assets/screenshots/Promosi%20-%20Cashback/List%20of%20Cashback.png)

### Summary Statistics

The page displays four key metrics at the top:

- **Cashback Paid**: Total cashback amount paid out (e.g., Rp0)
- **Cashback Redeemed**: Total cashback redeemed by customers (e.g., Rp0)
- **Redemption Rate**: Percentage of cashback that has been redeemed (e.g., 0%)
- **ROI**: Return on Investment percentage (e.g., 0%)

### Search Section

#### Search Bar
- **Search field**: "Cari nama Rule" (Search rule by name)
- Search icon to find specific rules

#### Action Button
- **Tambah Rule** (Add Rule): Button to create new cashback rule

### Cashback Rules Table

#### Table Columns
- **Rule Name**: Name of the cashback rule (e.g., "QRCampaign", "NextOrder1")
- **Condition When**: The trigger condition for the rule (e.g., "QrCampaignID == QR~-032bf5a3-399e-4df5-a025-21910b79f2fd", "Order count == 1")
- **Condition Then**: The outcome/action that happens when condition is met (e.g., "2 Conditions", "3 Conditions")
- **Action**: Three-dot menu for additional actions

### Example Rules

**Rule 1: QRCampaign**
- Condition When: QrCampaignID == QR~-032bf5a3-399e-4df5-a025-21910b79f2fd
- Condition Then: 2 Conditions

**Rule 2: NextOrder1**
- Condition When: Order count == 1
- Condition Then: 3 Conditions

### Pagination
- Showing 1-2 of 2

## Create Cashback Rule Page

![Create New Cashback Rule](../../assets/screenshots/Promosi%20-%20Cashback/Create%20New%20Cashback%20Rule.png)

### Cashback Configuration Section

#### Rule Name
- **Nama Rule** (Rule Name): Text input field with placeholder "Rule 1"

#### When Section (Conditions Trigger)
- **Pilih Kondisi** (Choose Condition): Dropdown to select condition type
- **Pilih Operator** (Choose Operator): Dropdown to select operator
- **Value field**: Input field for the condition value
- **+ Tambah Kondisi** (Add Condition): Button to add more conditions

#### Then Section (Actions/Results)
- **Pilih Kondisi** (Choose Condition): Dropdown to select result type
- **Expiry days**: Dropdown field
- **Value field**: Input field with default value "7" (days)
- **+ Tambah Hasil** (Add Result): Button to add more results

### Action Button
- **Save Cashback Settings**: Button to save the cashback rule configuration

## How to Use

### Create New Cashback Rule
1. Click **Tambah Rule** (Add Rule) button on List page
2. Enter rule name in "Nama Rule" field
3. In **When** section:
   - Select condition type from "Pilih Kondisi" dropdown
   - Select operator from "Pilih Operator" dropdown
   - Enter value in the value field
   - Click "+ Tambah Kondisi" to add more conditions if needed
4. In **Then** section:
   - Select result type from "Pilih Kondisi" dropdown
   - Set "Expiry days" from dropdown
   - Enter value (default: 7 days)
   - Click "+ Tambah Hasil" to add more results if needed
5. Click **Save Cashback Settings** to create the rule

### View Cashback Performance
1. Check "Cashback Paid" - total cashback distributed
2. Check "Cashback Redeemed" - how much customers used
3. Monitor "Redemption Rate" - percentage of cashback redeemed
4. Check "ROI" - return on investment from cashback program

### Edit or Manage Rules
1. Click three-dot menu next to rule in list
2. Select action to edit or manage the rule

## Rule Components

### Condition (When)
- Specifies the trigger condition for the cashback rule
- Can include multiple conditions combined together
- Examples: Campaign ID, Order count, Purchase amount

### Result (Then)
- Specifies what happens when condition is met
- Includes reward type and expiry period
- Example: Give cashback with 7-day expiry

## Next Steps

- Back to [Promotions Overview](.)
- View [Voucher](./voucher.md)
- View [Post Purchase Offer](./post-purchase-offer.md)
- View [QR Campaign](./qr-campaign.md)
