# Pengiriman (Shipping Management)

Manage shipments from a single warehouse location with FLIK's comprehensive shipping system. Handle packaging, logistics, and delivery tracking efficiently.

## Overview

Pengiriman (Shipping) allows you to:
- Create and manage shipments
- Select shipping carriers
- Track shipments in real-time
- Manage shipping costs
- Configure pickup times
- Generate shipping labels
- Communicate with customers

## Pengiriman List Page

### Accessing Pengiriman
1. Navigate to **FLIK Shipping** from main menu
2. Select **Pengiriman** or **Shipping**
3. View list of all shipments

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/List pengiriman page.png`

### List Features
- **View all shipments** from your warehouse
- **Search shipments** by order number, tracking, or customer
- **Filter shipments** by status (Pending, Shipped, Delivered, Returned, Cancelled)
- **Sort shipments** by date or tracking number
- **Quick actions**: View details, Print label, Edit, Cancel, Track

### Shipment Status
- **Draft**: Shipment created but not processed
- **Awaiting Pickup**: Ready for courier pickup
- **Picked Up**: Courier collected package
- **In Transit**: On the way to destination
- **Out for Delivery**: In delivery area
- **Delivered**: Successfully delivered
- **Pending Delivery**: Waiting for delivery attempt
- **Returned**: Package returned to sender
- **Cancelled**: Shipment cancelled
- **Undeliverable**: Cannot be delivered

## Creating a Shipment

### Step 1: Start Shipment Creation
1. Click **Buat Pengiriman** or **Create Shipment** button
2. Pop-up window opens: **Create Pengiriman Step 1**

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 1.png`

### Step 1: Select Warehouse
In the first step, select:

#### Warehouse Selection
- **Warehouse Name**: Choose warehouse location
- **Warehouse Address**: Displayed from selection
- **Warehouse Phone**: Contact number
- **Default Pickup Location**: Pre-filled

#### Shipment Type
- **Create Pengiriman Manual**: Single shipment creation
  - Used for one-off shipments
  - Detailed form for each shipment
  - Best for small volume
- **Bulk Order**: Multiple shipments at once
  - Used for batch shipments
  - Upload CSV file
  - Best for high volume
  - Different file in folder: `Create Pengiriman Step 2b` (Bulk variant)

1. Select warehouse
2. Choose shipment type
3. Click **Selanjutnya** or **Next**
4. Proceed to Step 2

### Step 2: Order Details (Manual)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 2.png`

Fill in order and shipping information:

#### Order Information
- **Order Number/ID**: Reference order
- **Order Date**: Date of original order
- **Customer Name**: Recipient name
- **Customer Email**: Email address
- **Customer Phone**: Contact number

#### Recipient Address
- **Recipient Name**: Person receiving package
- **Street Address**: Full delivery address
- **City**: Destination city
- **Province/State**: State or province
- **Postal Code**: ZIP code
- **Special Instructions**: Delivery notes

#### Package Details
- **Package Dimensions**: Length, Width, Height (cm)
- **Package Weight**: Total weight (kg)
- **Package Type**: Box, Envelope, Parcel, etc.
- **Number of Items**: Quantity in shipment
- **Item Description**: What's inside

#### Additional Options
- **Insurance**: Add shipping insurance
- **Signature Required**: Require recipient signature
- **Fragile**: Mark as fragile
- **Perishable**: Mark if perishable

### Step 2b: Bulk Upload (For Bulk Orders)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 2b 1.png` & `Step 2b 2.png`

For bulk shipments:

#### CSV File Format
```
Order Number | Customer Name | Email | Phone | Address | City | Province | ZIP | Weight
ORD-001 | John Doe | john@email.com | 081234567 | Jl Main 1 | Jakarta | DKI | 12210 | 1.5
ORD-002 | Jane Smith | jane@email.com | 085678901 | Jl Side 2 | Bandung | Jawa Barat | 40123 | 2.0
```

#### Upload Process
1. Download template
2. Fill in shipment details
3. Upload CSV file
4. System validates data
5. Click **Next** to proceed

### Step 3: Select Shipping Carrier

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 3.png`

Choose shipping options:

#### Available Carriers
- JNE
- J&T
- Pos Indonesia
- Grab Express
- GoSend
- Other regional carriers

#### Shipping Methods
- **Regular**: Standard delivery 3-5 days
- **Express**: Fast delivery 1-2 days
- **Overnight**: Next day delivery
- **Scheduled**: Choose delivery date

#### Shipping Information
- **Estimated Delivery**: Expected arrival date
- **Shipping Cost**: Price (auto-calculated)
- **Shipping Type**: As selected
- **Carrier**: Selected courier

#### Cost Details
Click **Detail** or **Rincian** to see:
- **Base Rate**: Carrier rate
- **Distance Surcharge**: If applicable
- **Weight Surcharge**: If applicable
- **Total Cost**: Final shipping cost

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Biaya Detail Pengiriman Pop up.png`

1. Select carrier and method
2. Review shipping cost
3. Click **Selanjutnya** or **Next**
4. Proceed to Step 4a

### Step 4a: Schedule Pickup Time

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 4a.png`

Schedule courier pickup:

#### Pickup Time Selection
Pop-up shows: **Pilih Waktu Pick Up** (Choose Pickup Time)

- **Pickup Date**: Select date
- **Pickup Time Window**: Choose time slot
  - Morning: 08:00 - 12:00
  - Afternoon: 12:00 - 17:00
  - Evening: 17:00 - 21:00
- **Driver Name**: Assigned driver (optional)
- **Notes**: Special pickup instructions

1. Select pickup date
2. Choose time window
3. Add special instructions
4. Confirm selection
5. Click **Selanjutnya** or **Next**

### Step 4b: Pickup Confirmation

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 4b.png`

Review pickup details:

- **Pickup Date**: Selected date
- **Pickup Time**: Selected time window
- **Driver Details**: Assigned driver info
- **Special Notes**: Pickup instructions
- **Ready Status**: Confirm packages ready

1. Verify all details
2. Confirm packages ready for pickup
3. Click **Selanjutnya** or **Next**

### Step 5: Shipment Summary

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 5.png`

Review complete shipment information:

#### Summary Information
- **Order Details**: Customer and order info
- **Shipping Details**: Address and destination
- **Carrier Information**: Courier and method
- **Shipping Cost**: Total cost
- **Pickup Schedule**: Date and time
- **Tracking Number**: Shipping reference
- **Estimated Delivery**: Expected arrival

1. Review all information
2. Verify accuracy
3. Click **Selanjutnya** or **Next**
4. Proceed to Step 6 for final confirmation

### Step 6: Final Confirmation

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengiriman Page/Create Pengiriman Step 6.png`

Complete shipment creation:

#### Final Actions
- **Generate Label**: Print shipping label
- **Send Notification**: Email to customer
- **Create Shipment**: Confirm and create

Options:
1. **Confirm & Create**: Complete shipment
2. **Save as Draft**: Save without sending
3. **Print Label**: Generate shipping label
4. **Email Customer**: Send tracking info

After confirmation:
- Shipment created
- Tracking number generated
- Customer notification sent
- Pickup scheduled
- Shipment visible in list

## Managing Shipments

### View Shipment Details
1. Click shipment from list
2. See all details:
   - Order information
   - Customer details
   - Shipping address
   - Carrier information
   - Shipping cost
   - Tracking number
3. View shipping status
4. Check delivery progress

### Edit Shipment
Edit only draft shipments:
1. Click **Edit** on draft shipment
2. Modify details
3. Update address if needed
4. Change carrier/method
5. Click **Save**

⚠️ **Note**: Cannot edit after shipment handed to courier

### Cancel Shipment
1. Click **Cancel** on pending shipment
2. Provide cancellation reason
3. Confirm cancellation
4. Shipment cancelled
5. Refund process initiated

### Print Label
1. Click **Print Label**
2. Choose printer
3. Select label format
4. Print shipping label
5. Attach to package

### Track Shipment
1. Click **Track** option
2. View real-time tracking
3. See location updates
4. Check estimated delivery
5. View delivery attempts

## Shipment Notifications

### Automatic Notifications
- Order shipped
- In transit
- Out for delivery
- Delivered
- Delivery issues

### Send Notifications
1. Click shipment
2. Click **Send Notification**
3. Choose recipient (customer/merchant)
4. Select notification type
5. Send

### Notification Templates
Customize notification messages:
1. Go to **Settings**
2. Select **Notification Templates**
3. Edit templates
4. Save changes

## Shipping Settings

Configure shipping preferences:

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengaturan Pengiriman/Pengaturan Pengiriman.png`

- **Default Carrier**: Primary courier
- **Pickup Schedule**: Regular pickup times
- **Insurance Options**: Enable/disable
- **Signature Requirements**: Default setting
- **Return Policy**: Return procedures

## Reports & Analytics

View shipping analytics:

**Screenshot Reference**: `/assets/screenshots/Laporan & Analisis FLIK Shipping/Laporan & Analisis FLIK Shipping.png`

- **Total Shipments**: Volume metrics
- **Delivery Success Rate**: On-time delivery %
- **Average Shipping Cost**: Cost metrics
- **Carrier Performance**: Comparison
- **Geographic Data**: By destination
- **Shipping Trends**: Over time

### Generate Reports
1. Go to **Reports**
2. Select date range
3. Choose report type
4. Download as PDF/Excel

## Best Practices

1. ✅ Accurate package dimensions
2. ✅ Complete address information
3. ✅ Timely shipment creation
4. ✅ Clear item descriptions
5. ✅ Regular tracking updates
6. ✅ Proactive communication
7. ✅ Proper packaging
8. ✅ Monitor carrier performance

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Pickup not scheduled | Check warehouse settings, select available time |
| Tracking not updating | Wait for carrier system sync (24 hours typically) |
| Address invalid | Verify complete address details |
| Carrier unavailable | Select alternative carrier |
| Cost too high | Check package dimensions, try different method |

## Tips

- **Batch shipments** when possible for better rates
- **Schedule pickups** during business hours
- **Monitor tracking** to address issues early
- **Keep customer informed** with updates
- **Compare carriers** for best rates
- **Review analytics** monthly

## Next Steps

- Back to [FLIK Shipping Overview](.)
- Check [Multiple Warehouse](./multiple-warehouse.md)
- View [Shipment Tracking](./lacak-pengiriman.md)
- Configure [Shipping Settings](./pengaturan-pengiriman.md)
