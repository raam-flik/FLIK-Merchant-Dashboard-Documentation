# Order Form Builder

Create custom order forms to collect customer information and process orders efficiently. Order forms allow you to customize the checkout experience with specific fields and flows.

## Overview

The Order Form Builder enables you to:
- Create custom order forms
- Customize form fields
- Set up form workflows
- Generate unique form URLs/slugs
- Collect customer information
- Process orders seamlessly

## Order Form List Page

### Accessing Order Forms
1. Navigate to **FLIK Checkout** from main menu
2. Select **Order Form** or **Formulir Pesanan**
3. View list of all created order forms

![Order Form List Page](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/List%20Order%20Form%20Page.png)

### List Features
- **View all order forms** created in your store
- **Search forms** by name or slug
- **Filter forms** by status (Active, Inactive, Draft)
- **Sort forms** by creation date
- **Quick actions**: View, Edit, Duplicate, Delete, Share, Analytics

### Form Status
- **Draft**: Form created but not active
- **Active**: Form published and accepting orders
- **Inactive**: Form temporarily disabled
- **Archived**: Form no longer in use

## Creating an Order Form

### Step 1: Start Form Creation

![Create Order Form Pop-up](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/Pop%20Up%20Create%20Order%20Form.png)

1. Click **Buat Order Form** or **Create Order Form** button
2. Pop-up window opens with form configuration options
3. Fill in form details as shown above

### Step 2: Form Configuration Pop-up

In the Create Order Form pop-up, enter:

#### Form Details
- **Form Name**: Display name for the form
- **Form Slug/URL**: Unique identifier (auto-generated or custom)
  - Example: `my-store-order-form` or `product-order-001`
- **Form Description**: Brief description of the form
- **Publish Status**: Draft or Published

#### Form Settings
- **Form Category**: Type of form (Order, Quote, Inquiry, etc.)
- **Default Currency**: Payment currency
- **Display Language**: Form language

### Step 3: Order Form Creation Page

![Order Form Creation Page](../../assets/screenshots/FLIK%20Checkout%20-%20Order%20Form%20Page/Order%20Form%20Creation%20Page.png)

1. Review entered information
2. Click **Selanjutnya** or **Next** button
3. You'll see the main form editor above where you can:
   - Add and customize form fields
   - Configure form layout
   - Set up payment options
   - Preview and publish form

## Order Form Creation Page

### Main Form Editor

The creation page allows you to:
- Add and customize form fields
- Configure form layout
- Set up payment options
- Preview form
- Publish form

### Add Form Fields

#### Available Field Types
1. **Text Input**: Single line text
2. **Text Area**: Multi-line text
3. **Email**: Email address field
4. **Phone**: Phone number field
5. **Number**: Numeric input
6. **Dropdown**: Select from options
7. **Radio Button**: Single choice
8. **Checkbox**: Multiple selections
9. **Date**: Date picker
10. **File Upload**: Document upload
11. **Product Selection**: Choose products
12. **Quantity**: Item quantity
13. **Price Input**: Pricing field
14. **Custom HTML**: Custom content

#### Adding a Field
1. Click **Add Field** or **Tambah Field**
2. Select field type
3. Configure field:
   - **Field Label**: Display name
   - **Field Name**: Internal identifier
   - **Placeholder**: Help text
   - **Required**: Mark as mandatory
   - **Validation**: Set validation rules
   - **Options**: Add choices (for dropdowns, radio, checkbox)
4. Save field
5. Field appears in form

### Form Layout

#### Section Organization
- **Add Section**: Organize fields in sections
- **Section Title**: Header for group of fields
- **Reorder Fields**: Drag to rearrange
- **Group Related Fields**: Organize by category

#### Example Form Structure
```
Section 1: Customer Information
├── Full Name (Required)
├── Email Address (Required)
├── Phone Number (Required)
└── Address (Required)

Section 2: Order Details
├── Product Selection (Required)
├── Quantity (Required)
├── Special Instructions
└── Additional Notes

Section 3: Billing
├── Billing Address (Optional)
├── Payment Method
└── Terms & Conditions (Required)
```

### Form Customization

#### Appearance Settings
- **Form Title**: Large heading
- **Form Description**: Introductory text
- **Background Color**: Form background
- **Button Color**: Submit button color
- **Font Style**: Typography settings
- **Logo**: Upload store logo
- **Theme**: Light/Dark theme

#### Advanced Settings
- **Redirect URL**: Where to send after submission
- **Thank You Message**: Custom success message
- **Notification Email**: Receive form submissions
- **CAPTCHA**: Anti-spam protection
- **Analytics Tracking**: Track form performance

### Payment Configuration

#### Payment Options
- **Enable Payments**: Accept payment via form
- **Payment Methods**: Select payment gateways
- **Currency**: Payment currency
- **Tax Rate**: If applicable

#### Product & Pricing
- **Add Products**: Include products in form
- **Dynamic Pricing**: Price based on selections
- **Shipping Cost**: Include shipping fee
- **Discount Code**: Allow discount codes

### Preview Form

1. Click **Preview** or **Pratinjau** button
2. See how form appears to customers
3. Test form fields
4. Check responsive design
5. Verify layout on mobile

### Publish Form

Once form is ready:
1. Review all settings
2. Click **Publish** or **Terbitkan** button
3. Form becomes active
4. Generate shareable link
5. Form accepts submissions

## Managing Order Forms

### View Form Details
1. Click form from list
2. See submission count
3. View form analytics
4. Access form settings
5. Check submitted data

### Edit Form
1. Click **Edit** on active form
2. Modify form fields
3. Update settings
4. Change appearance
5. Click **Save** to update

### Duplicate Form
1. Click **Duplicate** option
2. New form created with copy of original
3. Edit as needed
4. Save as new form

### Share Form
Generate shareable link:
1. Click **Share** button
2. Copy form link/URL
3. Share via:
   - Email
   - SMS
   - Social media
   - Website
   - QR Code

### Form Analytics
View form performance:
- **Total Views**: How many viewed form
- **Total Submissions**: Orders received
- **Conversion Rate**: View-to-submission ratio
- **Average Time**: Time to complete form
- **Abandonment Rate**: Incomplete submissions
- **Top Entry Source**: Where visitors came from

### View Submissions
1. Click form from list
2. Select **Submissions** or **Pengajuan**
3. View list of orders
4. See customer details
5. Export submission data
6. Download as CSV/Excel

## Form Fields Best Practices

### Customer Information Section
- Required fields marked clearly
- Logical order
- Pre-fill when possible
- Auto-suggest for common fields

### Product Selection
- Clear descriptions
- Product images
- Price display
- Stock availability indicator
- Quantity selector

### Payment Information
- Security assurance
- Clear pricing
- Discount code field
- Payment method options
- Terms checkbox

## Advanced Features

### Conditional Logic
- Show/hide fields based on selections
- Progressive disclosure
- Smart form flows
- Branching logic

### Integration Options
- Connect to CRM
- Sync to inventory system
- Webhook integration
- Email notification setup
- Zapier integration

### Automation
- Auto-reply emails
- Confirmation messages
- Assigned follow-up
- Auto-publish forms
- Scheduled form opening/closing

## Best Practices

1. ✅ Keep forms short and simple
2. ✅ Ask only essential questions
3. ✅ Use clear, simple language
4. ✅ Group related fields
5. ✅ Test before publishing
6. ✅ Mobile optimize
7. ✅ Track performance
8. ✅ Update regularly

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Form not saving | Check required fields, verify data |
| Slug already exists | Use different slug name |
| Field not showing | Check visibility settings, refresh |
| Payment not working | Verify payment gateway setup |
| Submissions not received | Check notification email settings |

## Tips

- **Test thoroughly** before publishing
- **Use templates** for common form types
- **Monitor analytics** to optimize
- **Collect only necessary** information
- **Update forms regularly** based on feedback
- **A/B test** different versions

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Invoice Management](./invoice.md)
- Check [Toko Offline (POS)](./toko-offline.md)
- View [Checkout Personalization](./checkout-personalization.md)
