# Pengaturan Pengiriman (Shipping Settings)

Configure and customize your shipping preferences, carriers, warehouses, and delivery settings.

## Overview

Pengaturan Pengiriman (Shipping Settings) allows you to:
- Configure shipping carriers
- Set shipping rates
- Manage warehouses
- Define pickup schedules
- Configure delivery options
- Set return policies
- Manage insurance settings

## Accessing Shipping Settings

1. Navigate to **FLIK Shipping** from main menu
2. Select **Pengaturan Pengiriman** or **Shipping Settings**
3. Access the settings page

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Pengaturan Pengiriman/Pengaturan Pengiriman.png`

## Carrier Configuration

### Add Shipping Carrier

#### Available Carriers
- JNE
- J&T
- Pos Indonesia
- Grab Express
- GoSend
- Lazada Express
- Shopee Logistics
- Other carriers

#### Carrier Setup Steps
1. Click **Add Carrier** or **Tambah Kurir**
2. Select carrier from list
3. Enter carrier details:
   - **Merchant ID**: Your account ID with carrier
   - **API Key**: Authentication key
   - **Account Number**: Account reference
   - **Contact Name**: Carrier contact
   - **Contact Phone**: Support number
4. Configure shipping methods:
   - Enable/disable methods
   - Set default method
   - Configure rates
5. Test connection
6. Save configuration

### Carrier Settings

#### Carrier Information
- **Carrier Name**: Display name
- **Status**: Active/Inactive
- **Priority**: Primary/Secondary
- **Coverage**: Service areas

#### Shipping Methods per Carrier
- **Regular**: Standard delivery
- **Express**: Fast delivery  
- **Overnight**: Next day
- **Scheduled**: Custom date

#### Rate Configuration
- **Base Rate**: Starting rate
- **Weight Multiplier**: Per kg cost
- **Distance Surcharge**: By distance
- **Dimensional Weight**: By size

#### Service Hours
- **Pickup Times**: Available hours
- **Processing Time**: Cutoff time
- **Weekend Service**: Yes/No
- **Holiday Service**: Yes/No

### Manage Carriers

#### Edit Carrier
1. Select carrier from list
2. Click **Edit**
3. Update settings
4. Test connection
5. Save changes

#### Deactivate Carrier
1. Click carrier
2. Click **Deactivate** or **Nonaktifkan**
3. Confirm action
4. Carrier no longer available
5. Can reactivate later

#### Remove Carrier
1. Click carrier
2. Click **Remove** or **Hapus**
3. Confirm deletion
4. Carrier deleted
5. Cannot be recovered

## Warehouse Management

### Add Warehouse

1. Click **Add Warehouse** or **Tambah Gudang**
2. Enter warehouse details:

#### Basic Information
- **Warehouse Name**: Display name
- **Location**: City/Province
- **Address**: Full address
- **Phone**: Contact number
- **Email**: Contact email
- **Manager**: Person in charge

#### Warehouse Hours
- **Opening Time**: Start time
- **Closing Time**: End time
- **Days Open**: Operating days
- **Holiday Closed**: Holiday schedule

#### Pickup Configuration
- **Pickup Available**: Yes/No
- **Pickup Times**: Morning/Afternoon/Evening
- **Pickup Lead Time**: Hours in advance needed
- **Max Pickup Requests**: Daily limit

#### Warehouse Type
- **Primary**: Main warehouse
- **Secondary**: Additional location
- **Returns**: Returns processing center
- **Storage**: Storage only

### Manage Warehouses

#### Edit Warehouse
1. Select warehouse
2. Click **Edit**
3. Update information
4. Save changes

#### Set Default Warehouse
1. Click warehouse
2. Click **Set as Default**
3. Used for new shipments
4. Can change anytime

#### View Warehouse Analytics
1. Click warehouse
2. View **Analytics**:
   - Shipments processed
   - Average processing time
   - Peak hours
   - Carrier usage
   - Cost metrics

### Warehouse Assignments

#### Assign Staff
1. Go to warehouse
2. Click **Manage Staff**
3. Add team members
4. Set roles (Manager, Staff, etc.)
5. Set permissions

#### Sync Inventory
1. Go to warehouse
2. Click **Inventory Sync**
3. Configure sync:
   - Sync frequency
   - Sync source
   - Manual/Automatic
   - Sync items

## Pickup Schedule Configuration

### Default Pickup Times

Set standard pickup schedule:

#### Pickup Windows
- **Morning**: 08:00 - 12:00
- **Afternoon**: 12:00 - 17:00
- **Evening**: 17:00 - 21:00
- **Custom**: Define custom times

#### By Carrier
Configure per carrier:
- Carrier A: 08:00-12:00, 14:00-17:00
- Carrier B: 09:00-17:00 continuous
- Carrier C: 13:00-19:00 only

#### By Day
Different schedules by day:
- **Weekdays**: Normal hours
- **Weekends**: Extended/Limited
- **Holidays**: Closed/Special hours
- **Off Days**: When pickup not available

### Manage Pickup Schedule

#### Create Schedule
1. Click **Create Schedule**
2. Set carrier
3. Define pickup windows
4. Set days and hours
5. Save schedule

#### Edit Schedule
1. Select schedule
2. Click **Edit**
3. Modify times
4. Update carriers
5. Save changes

#### View Calendar
1. Click **Calendar View**
2. See all pickup schedules
3. View by carrier
4. View by warehouse
5. Identify conflicts

## Delivery Settings

### Configure Delivery Options

#### Delivery Methods
- **Standard Delivery**: Normal shipping
- **Express Delivery**: Fast shipping
- **Scheduled**: Customer chooses date
- **Same Day**: Same day delivery
- **Next Day**: Next day delivery

#### Customer Options
- **Let customer choose**: Offer all options
- **Default method**: Recommended option
- **Hide expensive**: Hide premium options
- **Require selection**: Must choose

#### Delivery Notifications
- **Pickup notification**: When picked up
- **Transit update**: While in transit
- **Delivery notification**: When delivered
- **Failed attempt**: If delivery fails
- **Arrival window**: 2-hour window notice

### Signature Requirements

#### Signature Settings
- **Always required**: Signature mandatory
- **Optional**: Customer can choose
- **Never required**: No signature needed
- **High value**: Required for expensive items

#### Photo Proof
- **Require photo**: Delivery photo required
- **Optional photo**: Customer can decline
- **Never photo**: No photo requirement

## Return Policy Configuration

### Return Settings

1. Click **Return Policy**
2. Configure options:

#### Return Window
- **Days allowed**: How long to return (14, 30, 45, etc.)
- **From purchase date**: Starting point
- **From receipt**: Starting when received
- **Custom date**: Specific date

#### Return Conditions
- **Unopened only**: Must be sealed
- **Original condition**: No damage allowed
- **Any condition**: Accept any state
- **Restocking fee**: Percentage charge

#### Return Shipping
- **Free returns**: You pay shipping
- **Paid by customer**: Customer pays
- **Hybrid**: Customer chooses
- **No returns**: Not allowed

#### Return Process
1. Customer initiates return
2. Generate return label
3. Customer ships back
4. Receive at warehouse
5. Inspect and process
6. Refund or replacement

### Returns Address
- **Set return address**: Where to send
- **Multiple addresses**: By warehouse
- **Different address**: Separate from shipping
- **Clear communication**: Inform customers

## Insurance Settings

### Shipping Insurance

1. Click **Insurance Settings**
2. Configure options:

#### Insurance Coverage
- **Offer insurance**: Yes/No
- **Optional**: Customer chooses
- **Mandatory**: Always included
- **By value**: Based on amount

#### Insurance Rate
- **Percentage**: % of value
- **Fixed fee**: Flat amount
- **Tiered**: Based on amount ranges
- **Carrier included**: Coverage included

#### Coverage Amount
- **Coverage limit**: Maximum coverage
- **Minimum claim**: Minimum amount
- **Exclusions**: What's not covered
- **Deductible**: Customer's responsibility

#### Claims Process
- **Claim procedure**: How to file
- **Documentation**: Required documents
- **Timeline**: Processing time
- **Contact**: Who to contact

## Special Handling

### Item Restrictions

Configure items that need special handling:

- **Fragile Items**: Extra care, specific packaging
- **Hazardous Materials**: Special requirements
- **Electronics**: Damage prevention
- **Valuable Items**: Insurance recommended
- **Oversized**: Extra charges apply
- **Perishable**: Temperature controlled
- **Restricted Items**: Cannot ship

### Packaging Requirements

- **Minimum packaging**: Required standards
- **Recommended materials**: Best practices
- **Prohibited materials**: What not to use
- **Padding requirements**: How much protection
- **Label requirements**: Labeling rules

## Cost Management

### Shipping Rates

#### Set Shipping Rates
1. Go to **Rates**
2. Click **Add Rate**
3. Configure:
   - Carrier
   - Service level
   - Zone/Distance
   - Weight ranges
   - Price

#### Rate by Zone
- **Zone 1**: City delivery
- **Zone 2**: Province delivery
- **Zone 3**: Inter-island delivery
- **Custom**: Define your own

#### Rate by Weight
- **0-1 kg**: Base price
- **1-5 kg**: Different price
- **5-10 kg**: Tiered pricing
- **10+ kg**: Premium pricing

### Discount Rules

#### Volume Discounts
- **First 10**: No discount
- **11-50**: 5% discount
- **51-100**: 10% discount
- **100+**: 15% discount

#### Seasonal Discounts
- **Off-season**: Lower rates
- **Peak season**: Higher rates
- **Promotional**: Special events
- **Customer loyalty**: Repeat customer discount

## Notifications

### Configure Notifications

#### To Customers
- **Shipment created**: Order ready
- **Picked up**: Courier collected
- **In transit**: On the way
- **Out for delivery**: Today
- **Delivered**: Successfully received
- **Delivery failed**: Attempt failed
- **Returned**: Coming back

#### To Merchant
- **Pickup scheduled**: When pickup confirmed
- **Pickup failure**: When pickup fails
- **Delivery status**: Regular updates
- **Problem alert**: When issues occur
- **End of day**: Daily summary

#### Notification Methods
- **Email**: Email notifications
- **SMS**: Text messages
- **WhatsApp**: WhatsApp messages
- **In-app**: Dashboard notifications
- **Push**: Mobile app push

## Integration Settings

### API Configuration

#### API Keys
- **Generate key**: Create new API key
- **Revoke key**: Disable old key
- **View key**: Display key
- **Key permissions**: What access allowed

#### Webhook Settings
- **Webhook URL**: Where to send data
- **Webhook events**: Which events trigger
- **Retry policy**: Retry failed webhooks
- **Test webhook**: Send test data

#### Third-Party Integration
- **Inventory system**: Sync inventory
- **Accounting software**: Auto-billing
- **CRM**: Customer data sync
- **Email service**: Notification provider

## Testing & Validation

### Test Carrier Connection
1. Click carrier
2. Click **Test Connection**
3. System validates credentials
4. Success or failure message
5. Fix if needed

### Test Pickup Schedule
1. Create test shipment
2. Test each carrier
3. Verify pickup times available
4. Check cost calculation
5. Confirm process

### Validate Settings
1. Go to **Validation**
2. System checks all settings
3. Reports any issues
4. Provides recommendations
5. Fix issues if needed

## Reporting & Analytics

### Shipping Settings Reports

View effectiveness:
- **Carrier performance**: By carrier metrics
- **Delivery rates**: Success percentage
- **Cost analysis**: By carrier/method
- **Customer satisfaction**: Rating scores
- **Problem areas**: Common issues
- **Trend analysis**: Over time

## Best Practices

1. ✅ Keep settings updated
2. ✅ Test new configurations
3. ✅ Monitor carrier performance
4. ✅ Adjust rates regularly
5. ✅ Clear return policy
6. ✅ Transparent insurance
7. ✅ Regular backup
8. ✅ Review analytics monthly

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Carrier connection failed | Verify API key, check account |
| Pickup not available | Check warehouse hours, select different time |
| Rate not calculating | Verify rate configuration, check rules |
| Notification not sending | Check settings, verify email/SMS |
| Sync not working | Check API configuration, test connection |

## Tips

- **Test first**: Validate before going live
- **Monitor metrics**: Track carrier performance
- **Communicate clearly**: Be transparent with customers
- **Optimize costs**: Review rates regularly
- **Plan returns**: Clear return process
- **Document policies**: Write clear policies

## Next Steps

- Back to [FLIK Shipping Overview](.)
- Explore [Pengiriman (Single Warehouse)](./pengiriman.md)
- Check [Multiple Warehouse Shipping](./multiple-warehouse.md)
- View [Red Zone Checking](./cek-red-zone.md)
