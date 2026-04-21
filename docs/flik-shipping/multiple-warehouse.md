# Multiple Warehouse Shipping

Manage shipments from multiple warehouse locations with an optimized workflow. Ideal for distributed inventory across several locations.

## Overview

Multiple Warehouse Shipping allows you to:
- Ship from multiple warehouse locations
- Optimize warehouse selection
- Manage inventory across locations
- Streamline multi-location operations
- Handle complex fulfillment scenarios

## Key Difference from Pengiriman

| Aspect | Single Warehouse (Pengiriman) | Multiple Warehouse |
|--------|------------------------------|-------------------|
| Warehouse | 1 fixed location | Many locations |
| Workflow | Single warehouse selection | Warehouse selection part of flow |
| Entry Point | Select warehouse in Step 1 | Select warehouse in flow steps |
| Use Case | Single location store | Multi-location business |
| Complexity | Simple | More advanced |

## Multiple Warehouse List Page

### Accessing Multiple Warehouse Shipping
1. Navigate to **FLIK Shipping** from main menu
2. Select **Multiple Warehouse** or **Pengiriman Multi Gudang**
3. View list of shipments

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/List of Pengiriman From Multiple Warehouse.png`

### List Features
- **View all shipments** from all warehouses
- **Filter by warehouse**: Select specific location
- **Search shipments**: By order, tracking, customer
- **Status filtering**: Pending, Shipped, Delivered, etc.
- **Quick actions**: View, Edit, Track, Cancel

## Creating a Multi-Warehouse Shipment

### Step 1: Shipment Initialization
1. Click **Buat Pengiriman** or **Create Shipment** button
2. System initiates multi-warehouse flow
3. Proceed to **Pilih ekspedisi** (Choose Carrier) step

### Step 2: Choose Carrier (Pilih ekspedisi)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Pilih ekspedisi.png`

Select shipping carrier and method:

#### Carrier Selection
Available couriers:
- JNE
- J&T
- Pos Indonesia
- Grab Express
- GoSend
- Other carriers

#### Shipping Methods
- **Regular**: Standard delivery
- **Express**: Fast delivery
- **Overnight**: Next day delivery
- **Scheduled**: Custom date

#### Cost Information
- **Shipping Cost**: Auto-calculated
- **Estimated Delivery**: Expected arrival
- **Transit Time**: Days to delivery

Actions:
1. Select preferred carrier
2. Choose shipping method
3. Review cost
4. Click **Selanjutnya** or **Next**

### Step 3: Pick Up Time (Pick up time)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Pick Up Time.png`

Schedule the courier pickup:

#### Pickup Schedule
- **Pickup Date**: Select date
- **Pickup Time Window**: Morning/Afternoon/Evening
- **Preferred Warehouse**: Select if multiple available
- **Special Instructions**: Any notes

#### Pickup Confirmation
- **Warehouse Details**: Selected location
- **Address**: Pickup address
- **Contact**: Warehouse contact
- **Ready Status**: Confirm ready for pickup

Actions:
1. Choose pickup date
2. Select time window
3. Confirm warehouse
4. Add instructions if needed
5. Click **Selanjutnya** or **Next**

### Step 4: Upload Data (Upload Data)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Upload Data.png`

Upload shipment information:

#### Upload Methods
1. **CSV/Excel Upload**: Bulk upload data
2. **Manual Entry**: Enter individual shipments
3. **Template Download**: Get template file

#### CSV Format
```
Order Number | Warehouse | Customer Name | Email | Phone | Address | City | ZIP | Weight
ORD-001 | Jakarta | John Doe | john@email.com | 081234567 | Jl Main 1 | Jakarta | 12210 | 1.5
ORD-002 | Bandung | Jane Smith | jane@email.com | 085678901 | Jl Side 2 | Bandung | 40123 | 2.0
```

#### Data Validation
- System validates all entries
- Shows errors/warnings
- Allows corrections before proceeding

Actions:
1. Download template (if needed)
2. Upload data file
3. Review validation results
4. Correct any errors
5. Click **Selanjutnya** or **Next**

### Step 5: Loading State (Loading State)

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Loading State.png`

System processes shipment data:

#### Processing Information
- **Processing Status**: Current progress
- **Records Processed**: Count completed
- **Estimated Time**: Time remaining
- **Progress Bar**: Visual progress indicator

#### During Loading
- System validates data
- Calculates shipping costs
- Assigns tracking numbers
- Prepares shipments
- Optimizes warehouse routing

⚠️ **Note**: Do not close browser during processing

Actions:
1. Wait for processing to complete
2. Monitor progress
3. System proceeds automatically to next step

### Step 6: Summary 1 (Ringkasan 1)

First summary page showing:

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Ringkasan 1.png`

#### Summary Content
- **Total Shipments**: Number of orders
- **Total Cost**: Combined shipping cost
- **Warehouses Involved**: Locations used
- **Carrier Summary**: Courier breakdown
- **Timeline**: Processing summary

#### Information Displayed
- **By Warehouse**: Shipments per location
- **By Carrier**: Shipments per courier
- **By Status**: Current status overview
- **By Destination**: Shipments per city

Actions:
1. Review shipment summary
2. Check totals and costs
3. Verify warehouse distribution
4. Click **Selanjutnya** or **Next**

### Step 7: Summary 2 (Ringkasan 2)

Detailed shipment breakdown:

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Ringkasan 2.png`

#### Details Shown
- **Shipment List**: Each order details
- **Tracking Numbers**: For each shipment
- **Destinations**: Delivery addresses
- **Carrier Assignment**: Which courier for each
- **Cost per Shipment**: Individual costs
- **Pickup Schedule**: When to pickup

#### Options
- **Edit**: Modify specific shipments
- **Remove**: Remove individual shipment
- **Download**: Export summary
- **Print**: Print labels

Actions:
1. Review detailed list
2. Check each shipment accuracy
3. Verify pickup schedule
4. Modify if needed
5. Click **Selanjutnya** or **Next**

### Step 8: Summary 3 (Ringkasan 3)

Final confirmation before creation:

**Screenshot Reference**: `/assets/screenshots/FLIK Shipping - Multiple Warehouse/Ringkasan 3.png`

#### Final Review
- **Total Orders**: Final count
- **Total Cost**: Final amount
- **Pickup Schedule**: Confirmed pickup times
- **Tracking Numbers**: Generated numbers
- **Customer Notifications**: Status

#### Final Actions
1. **Confirm & Create**: Complete all shipments
2. **Generate Labels**: Print all labels
3. **Send Notifications**: Alert customers
4. **Download Summary**: Export report
5. **Cancel**: Discard changes

Actions:
1. Final review all details
2. Confirm shipment data
3. Click **Confirm** or **Konfirmasi**
4. All shipments created
5. Pickup scheduled with couriers
6. Customers notified
7. System returns to list

## Managing Multi-Warehouse Shipments

### View Shipment Details
1. Click shipment from list
2. See full details:
   - Warehouse location
   - Customer information
   - Shipping address
   - Carrier details
   - Tracking number
   - Cost breakdown

### Edit Shipments
Edit only uncommitted shipments:
1. Select shipment
2. Click **Edit**
3. Modify details
4. Save changes

### Bulk Actions
- **Bulk Print Labels**: Print multiple at once
- **Bulk Notifications**: Send to multiple customers
- **Bulk Cancel**: Cancel multiple shipments
- **Bulk Status Update**: Update multiple at once

### Track Multiple Shipments
1. Select multiple shipments
2. Click **Track All**
3. View tracking for all
4. Sort by status or warehouse

## Warehouse Optimization

### Warehouse Selection
System can auto-select optimal warehouse based on:
- **Closest to customer**: Minimize delivery time
- **Best inventory**: Item availability
- **Lowest cost**: Cost optimization
- **Smallest load**: Balance warehouse workload

### Warehouse Settings
Configure in **Settings**:
- **Default warehouse** for new shipments
- **Warehouse priority** order
- **Inventory sync** frequency
- **Operating hours** by warehouse

## Reports & Analytics

### Multi-Warehouse Reports
Access comprehensive reports:
- Shipments by warehouse
- Cost analysis by location
- Delivery performance by warehouse
- Warehouse utilization
- Geographic data
- Trend analysis

### Generate Reports
1. Go to **Reports**
2. Select date range
3. Choose warehouse(s)
4. Select report type
5. Download as PDF/Excel

## Best Practices

1. ✅ Keep inventory synced
2. ✅ Optimize warehouse selection
3. ✅ Monitor warehouse performance
4. ✅ Balance workload across locations
5. ✅ Regular accuracy checks
6. ✅ Communicate across warehouses
7. ✅ Track cost per warehouse
8. ✅ Analyze customer delivery times

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Warehouse not available | Verify warehouse is active, check hours |
| Data upload failed | Check CSV format, fix invalid entries |
| Processing taking long | Large batch - be patient, don't close |
| Cost higher than expected | Review carrier rates, compare alternatives |
| Tracking not updating | Check if pickup completed by courier |

## Tips

- **Batch by warehouse** when possible
- **Monitor warehouse capacity** regularly
- **Compare warehouse performance** metrics
- **Optimize routing** for cost efficiency
- **Test workflow** with small batch first
- **Review summaries** carefully before confirming

## Next Steps

- Back to [FLIK Shipping Overview](.)
- Explore [Single Warehouse Shipping](./pengiriman.md)
- Check [Shipment Tracking](./lacak-pengiriman.md)
- View [Red Zone Checking](./cek-red-zone.md)
