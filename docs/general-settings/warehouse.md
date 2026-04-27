# Warehouse Management (Pengaturan Warehouse)

Manage warehouse locations and their configurations from the Warehouse settings page.

## Accessing Warehouse Settings

1. Click the **Gear Icon** (⚙️) in the top navigation bar
2. Select **Warehouse** from the dropdown menu
3. You will be directed to the Warehouse Configuration page (Pengaturan Warehouse)

![Warehouse Page](../../assets/screenshots/Warehouse/Warehouse%20Page.png)

## Warehouse List Page

### Page Title
**Pengaturan Warehouse** (Warehouse Configuration)

### Search and Actions
- **Search Bar**: "Cari nama warehouse" (Search warehouse name)
- **Tambah Warehouse** (Add Warehouse) Button: Dark blue button in top right to create new warehouse

### Warehouse Table

#### Table Columns
- **Kode Warehouse** (Warehouse Code): Unique warehouse identifier
- **Nama Warehouse** (Warehouse Name): Display name of the warehouse
- **Kota** (City): Location/city of the warehouse
- **HP. PIC** (Phone - PIC): Contact phone number of person in charge
- **Action**: Edit button for each warehouse

## Creating a Warehouse

### Step 1: Click Add Warehouse
1. Click **Tambah Warehouse** (Add Warehouse) button
2. You will be directed to the Create New Warehouse form

### Step 2: Create Warehouse Form

![Create New Warehouse](../../assets/screenshots/Warehouse/Create%20New%20Warehouse.png)

The form is divided into several sections:

#### PIC Warehouse Section
**Person In Charge Information**

- **Nama depan** (First Name): PIC's first name
- **Nama belakang** (Last Name): PIC's last name
- **Email**: PIC's email address
- **Nomor handphone** (Phone Number): PIC's phone number

#### Informasi Warehouse Section
**Warehouse Information**

- **Kode Warehouse** (Warehouse Code): Unique warehouse identifier
- **External ID**: Optional external system ID
- **Nama Warehouse** (Warehouse Name): Display name
- **Cari Alamat** (Search Address): Address search with map
  - Interactive map showing location
  - Button: "Gunakan Lokasi Saat Ini" (Use Current Location)

#### Address Details Section

- **Provinsi** (Province): State/province selection
- **Kota** (City): City selection
- **Kecamatan** (District): District/sub-area selection
- **Kode Pos** (Postal Code): Dropdown selector for postal codes
- **Alamat Lengkap** (Full Address): Text area for complete address
- **Catatan untuk kurir (optional)** (Courier Notes): Optional special instructions for couriers

#### Jadwal Operasional Section
**Operational Schedule**

Operating days toggle switches:
- **Senin** (Monday)
- **Selasa** (Tuesday)
- **Rabu** (Wednesday)
- **Kamis** (Thursday)
- **Jumat** (Friday)
- **Sabtu** (Saturday)
- **Minggu** (Sunday)

Each day can be toggled on/off.

#### Ambil di Toko Section
**Store Pickup Settings**

Two toggle options:
- **Status**: Ternak Aktif / Aktif (Active/Inactive status)
- **Tetapkan menjadi warehouse aktif** (Set as Active Warehouse): Toggle to set as default warehouse

#### Action Button
- **Kembali** (Back/Return): Button at bottom to save warehouse

## Editing a Warehouse

### Step 1: Click Edit
1. From the Warehouse list, click **Ubah** (Edit) button on the warehouse row
2. You will be directed to the same warehouse form as "Create New Warehouse" but with pre-filled information

### Step 2: Modify Details
1. Update any warehouse information needed
2. Change address, contact details, or operational settings
3. Modify store pickup settings if needed

### Step 3: Save
1. Click **Kembali** (Back/Save) button to save changes
2. Changes are saved and you return to warehouse list

## Warehouse Information

### What You Can Manage
- Warehouse location and address
- Person in charge (PIC) details
- Warehouse code/identifier
- Operational hours/days
- Store pickup configuration
- Contact information

### Important Fields
- **Kode Warehouse**: Must be unique
- **Nama Warehouse**: Display name for customer communications
- **Lokasi**: Geographic location (selected on map)
- **Alamat Lengkap**: Complete delivery address
- **Jadwal Operasional**: Days warehouse is open
- **PIC Contact**: Reachable contact for warehouse management

## Best Practices

1. ✅ Use clear, descriptive warehouse names
2. ✅ Set accurate operational hours
3. ✅ Keep PIC contact information current
4. ✅ Add helpful courier notes for delivery personnel
5. ✅ Verify address on map
6. ✅ Set one warehouse as default/active
7. ✅ Update information when address changes
8. ✅ Use postal code selector for accuracy

## Tips

- **Search Function**: Use to quickly find warehouse by name
- **Map**: Drag marker to adjust exact pickup location
- **Toggle Days**: Set which days warehouse operates
- **Store Pickup**: Enable if customers can pick up orders
- **Courier Notes**: Add special instructions for delivery (gates, directions, etc.)

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Can't find warehouse | Use search bar to filter by name |
| Address not correct | Click on map and drag marker to correct location |
| Phone number format error | Verify format includes country code |
| Can't save | Ensure all required fields are filled |
| Warehouse code conflict | Use unique code for each warehouse |

## Next Steps

- Back to [General Settings](../general-settings.md)
- View [Profile Management](../profile.md)
- Explore [FLIK Shipping Documentation](../flik-shipping/)
