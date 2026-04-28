# Lacak Pengiriman (Shipment Tracking)

Track and monitor shipments using tracking numbers. Check real-time delivery status, location, and journey details.

## Overview

Lacak Pengiriman (Shipment Tracking) allows you to:
- Search shipments by tracking number (Nomor AWB)
- View detailed shipment information
- Track real-time delivery status
- See complete delivery timeline
- View photos and updates

## Accessing Shipment Tracking

1. Navigate to **FLIK Shipping** from main menu
2. Select **Lacak Pengiriman** or **Track Shipment**
3. Enter tracking number to search

## Empty State (Initial Search)

![Cek Resi Empty State](../../assets/screenshots/FLIK%20Shipping%20-%20Lacak%20Pengiriman/Cek%20Resi%20Empty%20State.png)

### Search Interface
- **Nomor AWB** (Tracking Number): Input field for tracking number
- **Helper text**: "Anda bisa memasukkan lebih dari satu nomor AWB, pisahkan dengan koma. Contoh: 012345678912, 012345678913"
- **Cek AWB button**: Click to search for tracking information

## Filled State (Tracking Results)

![Cek Resi Filled State](../../assets/screenshots/FLIK%20Shipping%20-%20Lacak%20Pengiriman/Cek%20Resi%20Filled%20State.png)

When tracking results are found, the page displays:

### Detail Pengiriman AWB (Shipment Details Section)

#### Key Information Fields
- **Status**: Current status (e.g., Sudah Diterima)
- **Nomor Resi** (Tracking Number): e.g., WYB-1710404285248
- **Kurir** (Courier): e.g., SiCepat
- **Layanan** (Shipping Method): e.g., REG

#### Additional Details
- **Tanggal Kirim** (Ship Date): e.g., 10 Sep, 2024 - 14:27 WIB
- **Pengirim** (Sender): e.g., Randy Orton
- **Metode Pembayaran** (Payment Method): e.g., COD
- **Penerima** (Recipient): e.g., Joko Wiwok Detok
- **No HP Penerima** (Recipient Phone): e.g., +6281234567890
- **Dikirim ke** (Shipped To): e.g., FlekHaus, BSD

### Riwayat Perjalanan (Delivery Journey Timeline)

The page displays a vertical timeline with:

#### Timeline Columns
- **Tanggal** (Date): Date and time of each event
- **Keterangan** (Description): Status update description (e.g., "Package has been delivered to Daffa")
- **Foto & Tanda Tangan** (Photo & Signature): Photo evidence of delivery

#### Timeline Events
Each entry shows:
- Timestamp (Date and time)
- Status message describing the shipment journey
- Photo attached (if available)
- Blue active indicator (●) for current/latest status
- Grey inactive indicators (○) for past events

#### Example Events Shown
- Package has been delivered to Daffa
- Package will be delivered to your address by
- Package has been arrived at CIBINONG Drop Point
- Package will be departed to CIBINONG Drop Point
- Package has been arrived at BOGOR Transit Center
- Package will be departed to BOGOR Transit Center
- Package has been arrived at JAKARTA Transit Center
- Package has been arrived at JAKARTA Drop Center
- Package will be departed to JAKARTA Drop Point
- Package has been processed at JAKARTA Drop Point

### Additional Sections (Expandable)

- **Detail Pengiriman AWB [Number]**: Expandable section for additional shipment details

## Search Instructions

Multiple tracking numbers can be entered:
- Enter one or more tracking numbers
- Separate multiple numbers with comma
- Example: 012345678912, 012345678913
- Click **Cek AWB** to search

## Next Steps

- Back to [FLIK Shipping Overview](.)
- Explore [Pengiriman (Single Warehouse)](./pengiriman.md)
- Check [Multiple Warehouse Shipping](./multiple-warehouse.md)
- View [Red Zone Checking](./cek-red-zone.md)
