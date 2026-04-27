# Order Form Builder

Create custom order forms to collect customer information and process orders efficiently. Order forms allow you to customize the checkout experience with specific fields and flows.

## Overview

The Order Form Builder enables you to:
- Create custom order forms
- Customize form fields
- Generate unique form URLs
- Collect customer information
- Process orders seamlessly

## Order Form List Page

### Accessing Order Forms
1. Navigate to **FLIK Checkout** from main menu
2. Select **Order Form** or **Formulir Pesanan**
3. View list of all created order forms

![Order Form List Page](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/List%20Order%20Form%20Page.png)

### Order Form Table

#### Table Columns
- **Order Form**: Name of the order form
- **Visitors**: Counter showing number of form visitors
- **Page Views**: Counter showing number of page views
- **Data Masuk**: Counter showing how many leads/submissions
- **Paid**: Counter showing how many people paid
- **Status**: Current form status
- **Action**: Available actions for the form

### Form Status
- **Draft**: Form created but not active
- **Active**: Form published and accepting orders
- **Inactive**: Form temporarily disabled

### Form Actions

Available actions from the Action column:

- **Preview**: Preview form as customers see it
- **Detail Order Form**: View form details and analytics
- **Salin Link**: Copy shareable form link
- **Ubah Order Form**: Edit form structure and fields
- **Publish Ulang**: Republish form
- **Hapus Order Form**: Delete form

## Creating an Order Form

### Step 1: Start Form Creation

![Create Order Form Pop-up](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/Pop%20Up%20Create%20Order%20Form.png)

1. Click **Buat Order Form** or **Create Order Form** button
2. Pop-up window opens with form configuration options
3. Fill in form details

#### Form Details
- **Form Name**: Display name for the form
- **Form Slug/URL**: Unique identifier (auto-generated or custom)

### Step 2: Order Form Creation Page

![Order Form Creation Page](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/Order%20Form%20Creation%20Page.png)

The order form editor where you can configure all form sections.

## Order Form Structure

### Default Form Sections

#### 1. Header Section
- **Image Upload**: Upload image for hero section at top of form

#### 2. Produk (Product) Section
Product information fields:
- **Nama Produk** (Product Name): Text field for product name
- **Harga Produk** (Product Price): Numerical field for product price
- **Harga Coret** (Strikethrough Price): Numerical field for original/strikethrough price
- **Unggah Gambar** (Upload Image): Upload product image
- **Deskripsi** (Description): Optional text area for product description

#### 3. Dimensi & Berat (Dimensions & Weight) Fields
- **Panjang Barang (cm)** (Length): Numerical field in centimeters
- **Lebar Barang (cm)** (Width): Numerical field in centimeters
- **Tinggi Barang (cm)** (Height): Numerical field in centimeters
- **Berat Barang (kg)** (Weight): Numerical field in kilograms

#### 4. Order Form Section
Customer information fields that users need to fill:
- **Nama** (Name): Text field for customer name
- **Nomor WhatsApp** (WhatsApp Number): Phone number field
- **Alamat** (Address): Text field for delivery address

#### 5. Teks di Button Section
- **Button Text**: Customize the text displayed on submit button
- **Button Color**: Choose color for submit button

#### 6. Pengaturan Iklan (Advertising Settings) - Optional
- **Facebook Pixel ID**: ID for Facebook Pixel tracking
- **CAPI Token**: Conversion API token for Facebook

### Additional Sections You Can Add

Merchants can add extra sections to customize the form further:

- **Teks** (Text): Add custom text/paragraphs
- **Image**: Add images between sections
- **Button**: Add additional buttons
- **Testimoni** (Testimonials): Add customer testimonials

## Managing Order Forms

### View Form Details
1. Click form from list
2. View form analytics
3. Check submission data
4. Access form settings

### Edit Form
1. Click **Ubah Order Form** (Edit Order Form) from action menu
2. Modify form sections
3. Update fields
4. Click **Save** to update

### Share Form
1. Click **Salin Link** (Copy Link) from action menu
2. Copy form URL
3. Share via:
   - Email
   - SMS
   - Social media
   - Website
   - QR Code

### Preview Form
1. Click **Preview** from action menu
2. See how form appears to customers
3. Test form submission
4. Check responsive design

### Publish Form
1. Click **Publish Ulang** (Republish) from action menu
2. Form becomes active if in Draft status
3. Form ready to accept submissions

### Delete Form
1. Click **Hapus Order Form** (Delete Order Form) from action menu
2. Confirm deletion
3. Form removed from system

### View Form Details
1. Click **Detail Order Form** from action menu
2. View all form information
3. See analytics and metrics
4. Access submission data

## Form Customization

### Organizing Sections
- Drag sections to reorder
- Add multiple instances of additional sections
- Customize each section independently

### Field Configuration
Each field in default sections can be customized:
- Set required/optional
- Add helper text
- Set field validation
- Configure placeholder text

## Form Performance Tracking

Monitor from the list page:
- **Visitors**: Total people who viewed form
- **Page Views**: Total page view count
- **Data Masuk**: Total submissions received
- **Paid**: Total completed payments

## Best Practices

1. ✅ Use clear product descriptions
2. ✅ Upload high-quality product images
3. ✅ Set accurate dimensions and weight
4. ✅ Use compelling button text
5. ✅ Test form before publishing
6. ✅ Monitor form analytics
7. ✅ Update forms regularly
8. ✅ Optimize for mobile

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Form not saving | Verify all required fields are filled |
| Slug already exists | Use different slug name |
| Form not appearing | Check form status is Active |
| Submissions not received | Verify form is published |
| Link not working | Refresh page and copy link again |

## Tips

- **Test thoroughly** before publishing
- **Use descriptive names** for forms
- **Add all product details** for better conversions
- **Customize button text** to match your message
- **Monitor visitors vs conversions** to optimize
- **Update product information** regularly

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Invoice Management](./invoice.md)
- Check [Toko Offline (POS)](./toko-offline.md)
- View [Checkout Personalization](./checkout-personalization.md)
