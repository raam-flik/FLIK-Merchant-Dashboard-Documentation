# Toko Offline (Cashier Management)

Manage multiple cashiers for your offline store operations.

## Overview

Toko Offline (Offline Store) allows you to:
- Manage multiple cashiers
- Create and activate cashier accounts
- Control cashier access and permissions

## Toko Offline List Page

### Accessing Toko Offline

![List Toko Offline Page](../../assets/screenshots/FLIK%20Checkout%20-%20Toko%20Offline%20Page/List%20Toko%20Offline%20Page.png)

1. Navigate to **FLIK Checkout** from main menu
2. Select **Toko Offline**
3. View list of all cashiers

### Cashier List Features

#### Search
- **Search Bar**: "Cari Nama Kasir atau Email" (Search cashier name or email)
- Search by cashier name or email address

#### Filter
- **Filter Role**: Filter cashiers by role/permission level

#### Sort
- **Sort by Tanggal Pembuatan** (Creation Date): Sort cashiers by when they were created

## Managing Cashiers

### Adding a Cashier

![Tambah Kasir Toko Offline Page](../../assets/screenshots/FLIK%20Checkout%20-%20Toko%20Offline%20Page/Tambah%20Kasir%20Toko%20Offline%20Page.png)

Click **Tambah Kasir** or **Add Cashier** button to create new cashier:

#### Cashier Details Form

Fill in the following information:

1. **Cashier Name**: Full name of cashier
2. **Email Address**: Cashier email
3. **Password**: Secure access password
4. **Permissions Level**: 
   - Admin: Full administrative access
   - Cashier: Standard cashier access

### Step 2: Cashier Selection and Actions

![Edit Kasir](../../assets/screenshots/FLIK%20Checkout%20-%20Toko%20Offline%20Page/Edit%20Kasir.png)

After creating cashiers, you can manage them by selecting them from the list:

#### Cashier List Table

The cashier list displays:
- **Checkbox**: Select checkbox on the left of each cashier to select them
- **Cashier Name**: Name of the cashier
- **Email**: Cashier email address
- **Status**: Current status (active or inactive)
- **Role**: Permission level (admin or user/cashier)
- **Creation Date**: When cashier account was created

#### Available Actions

When you select a cashier (checkbox), the following action buttons become available:

1. **Edit Kasir** (Edit Cashier): Edit cashier details and permissions
2. **Aktifkan Kasir** (Activate Cashier): Activate an inactive cashier
3. **Nonaktifkan Kasir** (Deactivate Cashier): Deactivate an active cashier

#### How to Select and Manage

1. Click the **checkbox** on the left of a cashier row
2. Cashier is now selected (checkbox shows blue checkmark)
3. Available action buttons appear:
   - Click **Edit Kasir** to modify cashier information
   - Click **Aktifkan Kasir** to activate if cashier is inactive
   - Click **Nonaktifkan Kasir** to deactivate if cashier is active

## Cashier Operations

### View Cashier Details
1. Click cashier from list
2. See cashier profile information
3. View assigned role
4. Check creation date and status

### Edit Cashier
1. Select cashier using checkbox
2. Click **Edit Kasir** (Edit Cashier) button
3. Update information
4. Modify permissions
5. Click **Save**

### Activate Cashier
1. Select cashier using checkbox
2. Click **Aktifkan Kasir** (Activate Cashier) button
3. Cashier status changes from inactive to active
4. Cashier can now login and work

### Deactivate Cashier
1. Select cashier using checkbox
2. Click **Nonaktifkan Kasir** (Deactivate Cashier) button
3. Confirm action
4. Cashier access disabled
5. Can be reactivated later

### Reset Cashier Password
1. Select cashier using checkbox
2. Click **Edit Kasir** to access password reset
3. Confirm request
4. New temporary password sent
5. Cashier must change on next login

## Best Practices

1. ✅ Create unique cashier accounts for each person
2. ✅ Set appropriate permission levels (Admin or Cashier)
3. ✅ Keep email information current
4. ✅ Deactivate unused cashier accounts
5. ✅ Regularly review active cashiers
6. ✅ Reset passwords when needed
7. ✅ Document cashier roles
8. ✅ Use checkbox to select before actions

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Can't find cashier | Use search bar to find by name or email |
| Cashier can't login | Reset password, verify credentials |
| Wrong permissions | Select cashier and edit role |
| Duplicate names | Use email to distinguish |
| Can't deactivate | Select checkbox first, then click action |

## Tips

- **Checkbox Selection**: Always select cashier using checkbox before taking action
- **Search Function**: Use to quickly find cashiers by name or email
- **Filter by Role**: Organize cashiers by permission level (Admin or Cashier)
- **Sort by Date**: View newest or oldest cashier accounts
- **Regular Review**: Check active cashiers monthly
- **Password Security**: Reset passwords regularly for security

## Next Steps

- Back to [FLIK Checkout Overview](.)
- Explore [Invoice Management](./invoice.md)
- Check [Order Form Builder](./order-form.md)
- View [Checkout Personalization](./checkout-personalization.md)
