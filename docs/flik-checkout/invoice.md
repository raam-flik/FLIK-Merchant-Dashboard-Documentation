# Invoice Management

Manage and create invoices for your customers with FLIK Invoice system. Invoices are formal billing documents for transactions.

## Overview

The Invoice Management system allows you to:
- Create professional invoices
- Send invoices to customers
- Track invoice payments
- Customize invoice templates
- Manage invoice records

## Invoice List Page

### Accessing the Invoice List

![List Invoice Page](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/List%20Invoice%20Page.png)

1. Navigate to **FLIK Checkout** from main menu
2. Select **Invoice** or **Faktur**
3. You'll see the list of all invoices displayed above

### List Features
- **View all invoices** created in your store
- **Search invoices** by invoice number, customer name, or date
- **Filter invoices** by status (Paid, Pending, Expired, Cancelled)
- **Sort invoices** by date, amount, or customer
- **Quick actions**: View, Edit, Delete, Send, Download

### Invoice Status
- **Draft**: Invoice created but not sent
- **Sent**: Invoice sent to customer
- **Viewed**: Customer has viewed the invoice
- **Paid**: Payment received
- **Overdue**: Payment not received after due date
- **Cancelled**: Invoice is cancelled

## Creating an Invoice

### Step 1: Start Invoice Creation

![Create Invoice Page](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/Create%20Invoice%20Page.png)

1. Click **Buat Invoice** or **Create Invoice** button
2. You'll be directed to the Create Invoice Page shown above
3. Fill in all the invoice details as described in the next sections

### Step 2: Fill Invoice Details

#### Invoice Information
- **Invoice Number**: Auto-generated or custom
- **Invoice Date**: Date invoice is created
- **Due Date**: Payment due date
- **Invoice Title**: Custom invoice name (optional)
- **Invoice Description**: Additional details

#### Customer Information
- **Customer Name**: Full name or business name
- **Customer Email**: Email address for sending invoice
- **Customer Phone**: Contact number
- **Customer Address**: Delivery or billing address
- **Tax ID**: Customer tax number (optional)

#### Billing Address
- **Address**: Complete address
- **City**: City name
- **Province/State**: State or province
- **Postal Code**: ZIP code
- **Country**: Country selection

### Step 3: Add Products

### Step 3: Add Products

![Pop Up Tambah Produk Invoice](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/Pop%20Up%20Tambah%20Produk%20Invoice.png)

#### Adding Products
1. Click **Tambah Produk Custom** button
2. The pop-up window shown above opens
3. Fill in product details:
   - **Product Name**: Item name
   - **Description**: Item description
   - **Quantity**: Number of items
   - **Unit Price**: Price per item
   - **Discount**: Optional discount
   - **Tax**: Tax rate (if applicable)
4. Click **Add** or **Tambah** to add product
5. Product appears in the list
6. Repeat for additional products

#### Product Line Items
Each product line shows:
- Product name and description
- Quantity
- Unit price
- Total price
- Edit/Delete options

### Step 4: Calculate Total

The system automatically calculates:
- **Subtotal**: Sum of all products
- **Discount**: Applied discount
- **Tax**: Calculated tax (if applicable)
- **Total**: Final amount due

#### Adjustment Options
- Apply additional discount
- Add shipping cost
- Add other charges/fees
- Add payment terms note

### Step 5: Add Notes & Terms

- **Notes**: Additional information for customer
- **Terms & Conditions**: Payment terms
- **Payment Instructions**: How to pay
- **Custom Message**: Personal message to customer

### Step 6: Review & Send

1. Review all invoice details
2. Preview invoice format
3. Choose action:
   - **Save as Draft**: Save without sending
   - **Send**: Send invoice to customer via email
   - **Send & Print**: Send email and open print dialog
   - **Download**: Save invoice as PDF

## Sending Invoices

### How to Send Invoice
1. Create or open invoice
2. Click **Send** or **Kirim** button
3. Verify customer email
4. Add custom message (optional)
5. Click **Send** confirmation
6. Invoice sent to customer

### Send Methods
- **Email**: Send invoice to customer email
- **SMS**: Send link via SMS (if enabled)
- **Whatsapp**: Share via WhatsApp (if integrated)
- **Direct Link**: Generate shareable link

## Managing Invoices

### View Invoice Details
1. Click invoice from list
2. See full invoice information
3. View payment status
4. See payment history
5. Download invoice PDF

### Edit Invoice
- Click **Edit** on draft invoices
- Modify customer information
- Update products
- Change amounts
- Update due date

⚠️ **Note**: Sent/Paid invoices may have limited edit options

### Delete Invoice
1. Click **Delete** or **Hapus** option
2. Confirm deletion
3. Invoice is removed from system

⚠️ **Note**: Can only delete draft or unpaid invoices with no payment records

### Download Invoice
- Click **Download** or **Unduh**
- Choose file format: PDF
- Save to your computer
- Print if needed

## Invoice Settings

### Customize Invoice Template
1. Go to Settings
2. Select **Invoice Templates**
3. Choose default template
4. Customize:
   - Colors and branding
   - Logo placement
   - Font styles
   - Layout
5. Save template

### Tax Configuration
- Set default tax rate
- Set tax per product
- Add tax exempt status
- Configure tax display

### Numbering System
- Set invoice numbering format
- Auto-increment numbers
- Prefix/Suffix configuration
- Starting number

## Payment Tracking

### Mark as Paid
1. Open paid invoice
2. View payment status
3. System auto-marks when payment received
4. Manual mark as paid option available

### Payment Methods Tracked
- Online payment
- Bank transfer
- Check
- Cash
- Other methods

### Payment History
- See all payments received
- View payment dates
- Check payment amounts
- View payment method
- Export payment records

## Invoice Reports

### View Invoice Analytics
- Total invoices created
- Total revenue
- Outstanding amount
- Overdue invoices
- Average payment time
- Payment success rate

### Generate Reports
1. Go to Analytics section
2. Select Invoice Reports
3. Choose date range
4. Select report type
5. Download or view report

![Laporan & Analisis FLIK Checkout](../../assets/screenshots/Laporan%20&%20Analisis%20-%20FLIK%20Checkout/Laporan%20&%20Analisis%20FLIK%20Checkout.png)

## Best Practices

1. ✅ Set clear due dates
2. ✅ Use descriptive product names
3. ✅ Include all relevant details
4. ✅ Send invoices promptly
5. ✅ Follow up on overdue invoices
6. ✅ Keep records organized
7. ✅ Use invoice templates
8. ✅ Regular backups

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Invoice not sending | Check customer email, verify email settings |
| Customer can't view | Check email spam folder, resend link |
| Calculation incorrect | Review tax settings, product prices |
| Can't edit invoice | Ensure invoice is still in draft status |
| Invoice number issue | Check numbering configuration |

## Tips

- **Use templates** for faster invoice creation
- **Set reminder dates** for follow-ups
- **Send invoices promptly** for faster payment
- **Customize messages** for better customer relations
- **Monitor overdue** invoices closely
- **Backup data** regularly

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Order Form Builder](./order-form.md)
- Check [Toko Offline (POS)](./toko-offline.md)
- View [Checkout Personalization](./checkout-personalization.md)
