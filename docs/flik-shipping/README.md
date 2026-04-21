# FLIK Shipping Module

Complete logistics and shipping management system for your online and offline store operations.

## Overview

FLIK Shipping provides comprehensive tools for managing shipments, tracking deliveries, and optimizing logistics operations. It includes single and multiple warehouse support, real-time tracking, and extensive shipping configuration.

## Features

### 1. Pengiriman (Single Warehouse Shipping)
Manage shipments from a single warehouse location with a complete 6-step workflow.
- Create shipments with detailed information
- Select shipping carriers and methods
- Schedule courier pickups
- Track shipments in real-time
- View shipping costs and timelines

[Read Pengiriman Documentation →](./pengiriman.md)

### 2. Multiple Warehouse Shipping
Manage complex shipments across multiple warehouse locations with optimized routing.
- Select carrier and delivery method
- Schedule pickups
- Upload shipment data in bulk
- System optimizes warehouse selection
- Comprehensive summaries before confirmation

[Read Multiple Warehouse Documentation →](./multiple-warehouse.md)

### 3. Lacak Pengiriman (Shipment Tracking)
Real-time tracking system for customers and merchants with detailed status updates.
- Track by tracking number or order ID
- View complete status timeline
- Real-time location updates
- Delivery estimation
- Customer-friendly tracking page

[Read Shipment Tracking Documentation →](./lacak-pengiriman.md)

### 4. Cek Red Zone (Check Red Zone)
Identify restricted delivery areas and calculate additional shipping costs.
- Check if address is in red zone
- View delivery impact
- Calculate surcharges
- See available carriers
- Plan accordingly

[Read Red Zone Documentation →](./cek-red-zone.md)

### 5. Pengaturan Pengiriman (Shipping Settings)
Comprehensive configuration for all shipping operations.
- Configure shipping carriers
- Manage warehouse locations
- Set pickup schedules
- Configure delivery options
- Manage return policies

[Read Shipping Settings Documentation →](./pengaturan-pengiriman.md)

## Quick Start

### 1. Initial Setup
- Configure shipping carriers
- Add warehouse locations
- Set pickup schedules
- Configure delivery options
- Test carrier connections

### 2. Create First Shipment
- Choose between single or multiple warehouse
- Follow step-by-step process
- Review and confirm details
- Generate shipping label
- Customer gets tracking info

### 3. Track Shipments
- Use tracking number or order ID
- Share tracking with customers
- Monitor delivery status
- Handle any issues

### 4. Manage Settings
- Update carrier rates
- Adjust pickup times
- Modify return policy
- Review analytics

## Shipping Flow Comparison

### Single Warehouse (Pengiriman)
```
Create Shipment → Select Warehouse → Add Order Details → Choose Carrier →
Schedule Pickup → Review & Confirm → Done
```

### Multiple Warehouse (Multi Gudang)
```
Start Flow → Choose Carrier → Schedule Pickup → Upload Data →
Processing → Summary 1 → Summary 2 → Final Confirmation → Done
```

## Feature Matrix

| Feature | Pengiriman | Multi Warehouse | Tracking | Red Zone | Settings |
|---------|-----------|-----------------|----------|----------|----------|
| Single Warehouse | ✅ | - | ✅ | - | ✅ |
| Multiple Warehouse | - | ✅ | ✅ | - | ✅ |
| Bulk Upload | Limited | ✅ | - | - | - |
| Real-time Tracking | ✅ | ✅ | ✅ | - | ✅ |
| Red Zone Check | ✅ | ✅ | - | ✅ | ✅ |
| Carrier Config | - | - | - | - | ✅ |
| Return Policy | ✅ | ✅ | - | - | ✅ |
| Insurance | ✅ | ✅ | - | - | ✅ |
| Analytics | ✅ | ✅ | ✅ | - | ✅ |

## Supported Carriers

- **JNE**: Nationwide coverage
- **J&T**: Fast delivery option
- **Pos Indonesia**: Government carrier
- **Grab Express**: Urban delivery
- **GoSend**: Same-day delivery
- **Lazada Express**: E-commerce focused
- **Shopee Logistics**: E-commerce focused
- **Regional Partners**: Local alternatives

## Shipping Methods

### By Speed
- **Regular**: 3-7 days, lowest cost
- **Express**: 1-3 days, medium cost
- **Overnight**: Next day, highest cost
- **Scheduled**: Custom date/time

### By Destination
- **Same City**: 1-2 days
- **Province**: 2-5 days
- **Inter-Island**: 5-10 days
- **Remote Areas**: 7-14 days (Red Zone)

## Red Zone Impact

Areas with delivery challenges:
- **Extended Timeline**: 5-10+ days vs normal 1-3 days
- **Additional Surcharge**: 20-50%+ extra cost
- **Limited Carriers**: Fewer options available
- **Manual Processing**: Special handling required
- **Pre-notification**: Inform customer upfront

## Address Validation

The system validates addresses for:
- **Format Correctness**: Proper address format
- **Postal Code**: Valid ZIP code
- **Coverage Area**: Carrier can deliver
- **Red Zone**: Special restrictions
- **Delivery Risk**: Potential issues

## Tracking Features

### Real-Time Updates
- Current location
- Status changes
- Estimated delivery
- Delivery window
- Contact information

### Customer Benefits
- Peace of mind
- Expected arrival
- Delivery address confirmation
- Contact courier
- Request adjustments

### Merchant Benefits
- Monitor performance
- Track carrier reliability
- Identify issues early
- Communicate with customers
- Analytics data

## Cost Management

### Transparent Pricing
- Base carrier rate
- Red zone surcharge
- Insurance premium
- Package handling
- Total displayed to customer

### Optimization
- Compare carriers
- Choose best option
- Bulk discounts available
- Seasonal rates
- Volume-based pricing

## Integration Points

### Connects With
- **FLIK Checkout**: Order fulfillment
- **Analytics**: Shipping performance
- **Financial**: Shipping costs
- **Marketing**: Customer communication
- **External Carriers**: API integration

## Best Practices

1. ✅ Check red zones before accepting orders
2. ✅ Be transparent about shipping times
3. ✅ Provide tracking promptly
4. ✅ Monitor carrier performance
5. ✅ Keep shipment information accurate
6. ✅ Communicate with customers
7. ✅ Optimize warehouse selection
8. ✅ Regular rate review

## Performance Metrics

Track and monitor:
- **On-time delivery rate**: % successful deliveries
- **Average delivery time**: Days to delivery
- **Carrier reliability**: By carrier performance
- **Cost efficiency**: Shipping cost per order
- **Customer satisfaction**: Feedback scores
- **Issue resolution**: Time to fix problems

## Troubleshooting

For common issues:
- Pickup not scheduled → Check warehouse hours
- Tracking delayed → Allow 24 hours for sync
- High costs → Check for red zone surcharge
- Carrier unavailable → Select alternative carrier
- Address validation failed → Verify address details

## Getting Help

- Click **Help** (?) icon in dashboard
- View [Pengaturan Pengiriman](./pengaturan-pengiriman.md) for configuration help
- Contact carrier directly for tracking issues
- Email support@flik.co.id

## Module Navigation

- [Back to Main Documentation](../)
- [FLIK Checkout Documentation](../flik-checkout/)
- [Promotions Documentation](../promotions/)
- [Analytics Documentation](../analytics/)
- [Financial Documentation](../financial/)

---

**Last Updated**: April 21, 2026
**Current Version**: 1.0.0
