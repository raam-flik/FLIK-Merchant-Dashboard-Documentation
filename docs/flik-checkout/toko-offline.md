# Toko Offline (Point of Sale)

Manage your offline store operations using the Point of Sale (POS) system. Handle in-store transactions and manage cashiers efficiently.

## Overview

Toko Offline (Offline Store) is the POS system that allows you to:
- Manage in-store sales
- Process point-of-sale transactions
- Manage multiple cashiers
- Track inventory in real-time
- Generate in-store receipts
- Sync with online store

## Toko Offline List Page

### Accessing Toko Offline
1. Navigate to **FLIK Checkout** from main menu
2. Select **Toko Offline** or **Toko Luring**
3. View list of all offline stores

**Screenshot Reference**: `/assets/screenshots/FLIK Checkout - Toko Offline Page/List Toko Offline Page.png`

### List Features
- **View all stores** in your organization
- **Search stores** by name or location
- **Filter stores** by status (Active, Inactive, Draft)
- **Sort stores** by creation date
- **Quick actions**: View, Edit, Manage Cashiers, Analytics, Delete

### Store Status
- **Active**: Store operational and accepting transactions
- **Inactive**: Store temporarily closed
- **Draft**: Store not yet published
- **Archived**: Store no longer in use

## Creating a New Toko Offline

### Step 1: Access Store Creation
1. Click **Tambah Toko** or **Add Store** button
2. Fill in store details

### Step 2: Store Information

Enter the following details:

#### Basic Information
- **Store Name**: Name of your offline store
- **Store Location**: Physical address
- **Store Phone**: Contact number
- **Store Email**: Contact email
- **Store Code/ID**: Unique identifier for store
- **Manager Name**: Store manager
- **Manager Contact**: Manager phone/email

#### Store Settings
- **Currency**: Transaction currency
- **Tax Rate**: Store-specific tax (if applicable)
- **Operating Hours**: Store hours
- **Timezone**: Store timezone
- **Language**: Preferred language

#### Store Configuration
- **Inventory Sync**: Auto-sync with online inventory
- **Receipt Format**: Receipt template
- **Discount Permission**: Enable/disable discounts
- **Return Policy**: Store return rules
- **Payment Methods**: Accepted payment types

### Step 3: Review & Save
1. Review all store details
2. Click **Save** or **Simpan**
3. Store created and ready for setup

## Managing Cashiers

### Cashier List Page

After creating a store, manage cashiers:

**Screenshot Reference**: `/assets/screenshots/FLIK Checkout - Toko Offline Page/List Toko Offline Page.png`

### View Cashiers
1. Click store from list
2. View **Cashiers** or **Kasir** section
3. See list of all assigned cashiers
4. View status (Active, Inactive)
5. Check last activity

### Adding a Cashier

Click **Tambah Kasir** or **Add Cashier**:

**Screenshot Reference**: `/assets/screenshots/FLIK Checkout - Toko Offline Page/Tambah Kasir Toko Offline Page.png`

#### Cashier Details Form
1. **Cashier Name**: Full name of cashier
2. **Employee ID**: Unique employee identifier
3. **Email Address**: Cashier email
4. **Phone Number**: Contact number
5. **PIN/Password**: Secure access code
6. **Permissions Level**: 
   - Full Access: All transaction types
   - Limited: Restricted transactions
   - View Only: Reporting only
7. **Assignment**: Assign to specific shift(s)

#### Additional Settings
- **Commission Rate**: If applicable
- **Daily Limit**: Max transaction amount
- **Discount Authority**: Can approve discounts
- **Return Authority**: Can process returns
- **Void Authority**: Can void transactions

### Step 2: Cashier Activation
1. Review cashier details
2. Click **Confirm** or **Simpan**
3. Cashier account created
4. Cashier receives login credentials
5. Cashier can start transactions

## Managing Stores

### Edit Store Information
1. Click store from list
2. Click **Edit** button
3. Modify store details
4. Update configuration
5. Click **Save**

### View Store Analytics
1. Click store from list
2. View **Analytics** or **Laporan**
3. See store performance:
   - Daily sales
   - Transactions count
   - Top products
   - Best performing hours
   - Customer count
   - Average transaction value

### Store Settings

#### Transaction Settings
- **Receipt Format**: Template style
- **Receipt Printer**: Configure printer
- **Receipt Footer**: Custom message
- **Receipt Email**: Option to email receipt

#### Payment Settings
- **Payment Methods**: Cash, Card, etc.
- **Card Processor**: Credit card gateway
- **Installment Options**: If applicable
- **Payment Terms**: Payment conditions

#### Inventory Settings
- **Stock Tracking**: Enable real-time tracking
- **Low Stock Alert**: Notification threshold
- **Stock Adjustment**: Manual adjustments
- **Inventory Sync**: Online sync frequency

#### Discount & Promotions
- **Cashier Discount**: Allow cashier to give discounts
- **Max Discount**: Maximum discount amount
- **Discount Requires Approval**: Manager approval needed
- **Promotion Integration**: Apply online promotions

## Cashier Management

### View Cashier Details
1. Click cashier from list
2. See cashier profile
3. View performance metrics
4. Check transaction history
5. Review shift details

### Edit Cashier
1. Click cashier from list
2. Click **Edit**
3. Update information
4. Modify permissions
5. Click **Save**

### Deactivate Cashier
1. Click cashier from list
2. Click **Deactivate** or **Nonaktifkan**
3. Confirm action
4. Cashier access disabled
5. Can be reactivated later

### Reset Cashier Password
1. Click cashier from list
2. Click **Reset Password** or **Reset PIN**
3. Confirm request
4. New temporary password sent
5. Cashier must change on next login

### Cashier Performance Report
View cashier metrics:
- **Total Sales**: Revenue generated
- **Transaction Count**: Orders processed
- **Average Transaction**: Average sale value
- **Discount Frequency**: Discounts given
- **Return Rate**: Returns processed
- **Accuracy Score**: Transaction accuracy

## Point of Sale Operations

### Starting a Shift
1. Cashier logs into POS system
2. Enter PIN/password
3. Select store
4. Start shift (with opening balance)
5. System ready for transactions

### Processing a Transaction
1. Scan or select products
2. Enter quantity
3. Apply discounts if authorized
4. Select payment method
5. Process payment
6. Print receipt
7. Transaction complete

### Transaction Types
- **Sale**: Standard purchase
- **Refund**: Return transaction
- **Exchange**: Product exchange
- **Void**: Cancel transaction
- **Return**: Process returns
- **Adjustment**: Inventory adjustment

### Closing a Shift
1. Complete all transactions
2. Click **Close Shift**
3. Enter closing balance (cash)
4. System calculates variance
5. Review transaction summary
6. Confirm and close
7. Shift complete

## Store Synchronization

### Online-Offline Sync
- Products sync from online store
- Inventory updates in real-time
- Pricing synchronized
- Promotions applied to offline
- Customer data synced

### Sync Settings
1. Go to **Store Settings**
2. Select **Sync Configuration**
3. Set sync frequency
4. Choose sync items
5. Enable/disable auto-sync

## Reporting & Analytics

### Store Dashboard
View key metrics:
- **Daily Sales**: Revenue today
- **Active Cashiers**: Online cashiers
- **Transactions**: Today's order count
- **Top Products**: Best sellers
- **Payment Methods**: Payment breakdown

### Detailed Reports
Access reports for:
- **Sales Report**: Daily/monthly sales
- **Inventory Report**: Stock levels
- **Cashier Report**: Cashier performance
- **Transaction Report**: Individual transactions
- **Shift Report**: Shift summaries
- **Customer Report**: Customer data

### Generate Reports
1. Go to **Reports** or **Laporan**
2. Select report type
3. Choose date range
4. Click **Generate**
5. Download as PDF/Excel

## POS Hardware

### Supported Devices
- Receipt printers
- Barcode scanners
- Payment terminals
- Cash drawers
- Customer displays
- Touch screens

### Hardware Setup
1. Go to **Hardware Settings**
2. Connect POS devices
3. Configure device settings
4. Test connections
5. Save configuration

## Security & Compliance

### Access Control
- Cashier login required
- PIN/password protection
- Role-based permissions
- Transaction limits
- Approval workflows

### Audit Trail
- All transactions logged
- User activity tracked
- Change history recorded
- Payment verification
- Receipt retention

### Data Security
- Encrypted transactions
- Secure payment processing
- PCI compliance
- Regular backups
- Data protection

## Best Practices

1. ✅ Train cashiers thoroughly
2. ✅ Monitor cashier performance
3. ✅ Regular inventory audits
4. ✅ Secure POS terminals
5. ✅ Maintain accurate records
6. ✅ Daily shift reconciliation
7. ✅ Regular system updates
8. ✅ Customer receipt copies

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Cashier can't login | Reset password, check credentials |
| Inventory not syncing | Check sync settings, verify connection |
| Payment not processing | Verify payment gateway, check balance |
| Printer not working | Check connection, reinstall driver |
| Transaction failed | Retry transaction, check network |

## Tips

- **Regular backups** of transaction data
- **Monitor sales trends** to optimize inventory
- **Train new cashiers** on procedures
- **Reconcile shifts** daily
- **Update products** from online store
- **Review analytics** regularly

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Invoice Management](./invoice.md)
- Check [Order Form Builder](./order-form.md)
- View [Checkout Personalization](./checkout-personalization.md)
