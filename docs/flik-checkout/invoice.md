# Invoice Management

Manage and create invoices for your customers with FLIK Invoice system. Invoices are formal billing documents for transactions.

## Overview

The Invoice Management system allows you to:
- Create professional invoices
- Send invoices to customers
- Track invoice payments
- Manage invoice records
- Access payment links

## Invoice List Page

### Accessing the Invoice List

![List Invoice Page](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/List%20Invoice%20Page.png)

1. Navigate to **FLIK Checkout** from main menu
2. Select **Invoice**
3. You'll see the list of all invoices

### List Page Layout
The Invoice list page contains:

#### Header Section
- Page title: "Invoice"
- Top right: "Buat Invoice" (Create Invoice) button in dark blue
- Search bar: "Cari data order" (Search order data) with search icon

#### Invoice Table Columns
- **ID Cart**: Invoice ID/reference number (e.g., #00052)
- **Order/Nama Cart** (Order/Invoice Name): Invoice name or description (e.g., "Botol fancy")
- **Shopper** (Customer): Customer name or identifier (shows "-" if not set)
- **Tanggal Dibuat** (Created Date): Invoice creation date (e.g., "02 Apr, 2026")
- **Total**: Invoice total amount (e.g., "Rp1" or "Rp25.000")
- **Link Cart** (Invoice Link): "Salin link" (Copy link) button to share invoice with customer

### List Features
- **Search invoices**: Use search bar to find invoices by order data
- **View all invoices**: Scroll to see all created invoices
- **Copy invoice link**: "Salin link" button to get shareable payment link
- **Quick access**: Click invoice row to view or manage

### Invoice Information Shown
- Invoice unique ID (cart ID)
- Invoice name or order reference
- Customer/shopper information
- Creation date
- Invoice amount in currency
- Shareable link for payment

## Creating an Invoice

### Step 1: Start Invoice Creation

![Create Invoice Page](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/Create%20Invoice%20Page.png)

1. Click **Buat Invoice** (Create Invoice) button in top right
2. You'll be directed to the Create Invoice Page shown above
3. Fill in all the invoice details

### Step 2: Fill Invoice Details

#### Invoice Information
- **Invoice Name/Title**: Name for the invoice
- **Invoice Date**: When invoice is created
- **Due Date**: Payment deadline

#### Customer Information
- **Customer/Shopper Name**: Customer name
- **Customer Email**: Email for sending invoice
- **Customer Phone**: Contact number (optional)

#### Order/Reference Information
- **Order Reference**: Order number or reference
- **Other details**: As needed

### Step 3: Add Products

![Pop Up Tambah Produk Invoice](../../assets/screenshots/FLIK%20Checkout%20-%20Invoice%20Page/Pop%20Up%20Tambah%20Produk%20Invoice.png)

#### Adding Products
1. Click button to add products
2. Pop-up window opens
3. Fill in product details:
   - **Product Name**: Item name
   - **Description**: Item description
   - **Quantity**: Number of items
   - **Unit Price**: Price per item
   - **Discount**: Optional discount (if applicable)
4. Click button to add product
5. Product appears in the list
6. Repeat for additional products

#### Product Line Items
Each product line shows:
- Product name
- Quantity
- Unit price
- Total price (calculated)
- Edit/Delete options

### Step 4: Automatic Calculation

The system automatically calculates:
- **Subtotal**: Sum of all products
- **Tax**: Calculated if applicable
- **Total**: Final amount due

### Step 5: Add Notes & Payment Information

- **Notes**: Additional information for customer
- **Payment Instructions**: How customer should pay
- **Custom Message**: Personal message to customer

### Step 6: Review & Create

1. Review all invoice details
2. Click button to create invoice
3. Invoice is created and ready to send

## Managing Invoices

### Copy Invoice Link
From the invoice list:
1. Find invoice in the table
2. Click **Salin link** (Copy link) button
3. Link is copied to clipboard
4. Share link with customer via:
   - Email
   - WhatsApp
   - SMS
   - Any communication channel

### View Invoice Details
1. Click invoice ID or name in the list
2. View complete invoice information
3. See all details and amounts
4. Access sharing and payment options

### Send Invoice to Customer
1. Copy the invoice link using "Salin link" button
2. Send link to customer via preferred channel
3. Customer can access and pay via the link

### Invoice Payment
Customers can:
- Click invoice link
- Review invoice details
- Select payment method
- Complete payment
- Receive confirmation

## Invoice Organization

### Search & Find
- Use **Cari data order** search bar to find invoices
- Search by:
  - Invoice ID
  - Order name
  - Customer name
  - Or other order data

### View All Invoices
- Scroll through the list to view all created invoices
- Each row shows key information
- Dates help identify recent invoices

## Best Practices

1. ✅ Use clear, descriptive invoice names
2. ✅ Include accurate customer information
3. ✅ Add detailed product descriptions
4. ✅ Share invoice links promptly
5. ✅ Follow up on unpaid invoices
6. ✅ Keep clear payment terms
7. ✅ Save important invoice references
8. ✅ Monitor invoice amounts

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Can't find invoice | Use search bar, check created date |
| Link not copying | Click "Salin link" button again, check clipboard |
| Customer can't access | Resend link, verify email/communication channel |
| Wrong amount | Check product quantities and prices in invoice |
| Missing customer info | Edit invoice to add customer details |

## Tips

- **Generate payment link immediately** after creating invoice
- **Share links via multiple channels** for reliability
- **Use consistent naming** for easy identification
- **Save important invoice IDs** for reference
- **Monitor unpaid invoices** regularly

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Order Form Builder](./order-form.md)
- Check [Toko Offline (POS)](./toko-offline.md)
- View [Checkout Personalization](./checkout-personalization.md)
