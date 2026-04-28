# Cek Red Zone (Check Red Zone)

Check if an address is in a red zone area. Identify delivery restrictions and carrier availability for specific areas.

## Overview

Cek Red Zone (Check Red Zone) allows you to:
- Check if an address is in a red zone
- View which couriers can deliver to the area
- See carrier availability status
- Identify delivery restrictions

## Accessing Red Zone Check

1. Navigate to **FLIK Shipping** from main menu
2. Select **Cek Red Zone** or **Check Red Zone**
3. Use the checking tool

## Red Zone Check Interface

### Step 1: Empty State (Initial Search)

![Check Red Zone](../../assets/screenshots/FLIK%20Shipping%20-%20Cek%20Red%20Zone/Check%20Red%20Zone.png)

The initial interface shows:

#### Search Form
- **Input Field**: "Cari area dengan nama kabupaten, kelurahan, atau kode pos" (Search area by district name, village, or postal code)
- **COD Filter**: Dropdown to filter by COD option
- **Check Area Button**: Click to search the area

#### Helper Message
- **Title**: "Hindari Risiko Dengan Cek Red Zone" (Avoid Risk By Checking Red Zone)
- **Description**: "Hindari risiko keterlambatan dan kerugian dengan cek Red Zone sebelum pengiriman" (Avoid the risk of delays and losses by checking Red Zone before shipment)

### Step 2: Search Results with Suggestions

![Check Red Zone-1](../../assets/screenshots/FLIK%20Shipping%20-%20Cek%20Red%20Zone/Check%20Red%20Zone-1.png)

When searching (e.g., "Gunung"), the system displays matching location suggestions:

#### Suggested Locations Format
- **Postal Code** - Location Name, District, Province

#### Example Results
- 45151 - Gunung Jati, Kab. Cirebon, Jawa Barat
- 26256 - Gunung Omeh, Kab. Lima Puluh Kota, Sumatera Sealtan
- 34683 - Gunung Agung, Kab. Tulang Bawang Barat, Lampung
- 35379 - Gunung Alip, Kab. Tanggamus, Lampung
- 60294 - Gunung Anyar, Kota Surabaya, Jawa Timur
- 73753 - Gunung Bintang Awai, Kab. Barito Selatan, Kalimantan Tengah

### Step 3: Loading State

![Check Red Zone-2](../../assets/screenshots/FLIK%20Shipping%20-%20Cek%20Red%20Zone/Check%20Red%20Zone-2.png)

After selecting an area, the system shows a loading state:

#### Loading Interface
- **Selected Area** displayed in search field (with X button to clear)
- **Loading Indicator**: Spinning circular progress indicator
- **Status Message**: "Sedang mengecek daerah tujuan..." (Checking destination area...)

### Step 4: Red Zone Results

![Check Red Zone-3](../../assets/screenshots/FLIK%20Shipping%20-%20Cek%20Red%20Zone/Check%20Red%20Zone-3.png)

After checking, the results display red zone information for multiple couriers:

#### Result Message
"Berikut informasi red zone untuk pengiriman Non - COD daerah [Area Name]."
(Here is red zone information for Non-COD shipments to [Area Name].)

#### Courier Cards Grid
The system displays courier information in a 3-column grid:

##### Carrier Card Format
- **Courier Logo**: Company logo icon
- **Courier Name**: e.g., ID Express, JNE, Ninja Express, SiCepat, etc.
- **Status Badge**: Shows either:
  - "Tidak Red Zone" (Not Red Zone) - light green badge
  - "Red Zone" (Red Zone) - red badge

##### Couriers Shown
1. **ID Express** - Tidak Red Zone
2. **Anter Aja** - Tidak Red Zone
3. **J&T** - Tidak Red Zone
4. **JNE** - Tidak Red Zone
5. **Ninja Express** - Tidak Red Zone
6. **SiCepat** - Tidak Red Zone
7. **Lion Parcel** - Tidak Red Zone
8. **Paxel** - Red Zone
9. **SAP** - Red Zone
10. **Mr. Speedy** - Red Zone
11. **TiKi** - Red Zone
12. **RPX** - Red Zone

## How to Use

1. Navigate to Cek Red Zone page
2. Enter location by:
   - District/village name (kabupaten/kelurahan)
   - Postal code
   - City name
3. Optionally select COD filter
4. Click **Check Area** button
5. Wait for results
6. Review courier availability:
   - Green "Tidak Red Zone" = Courier can deliver
   - Red "Red Zone" = Courier cannot deliver / has restrictions
7. Choose appropriate courier based on red zone status

## Next Steps

- Back to [FLIK Shipping Overview](.)
- Explore [Pengiriman (Single Warehouse)](./pengiriman.md)
- Check [Shipment Tracking](./lacak-pengiriman.md)
- View [Multiple Warehouse Shipping](./multiple-warehouse.md)
