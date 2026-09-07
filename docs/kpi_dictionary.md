# KPI Dictionary

This file explains the main KPI terms used in the Metro by T-Mobile store performance analytics demo project.

The KPI definitions are written in simple business language so the notebooks, dashboard and analysis outputs are easier to understand.

---

## Important Note

The public version of this project uses synthetic demo data. The KPI names are based on the structure of the practicum project, but the values in this repository are not real company performance data.

Some fields, such as promotion flags, local event flags, and inventory issue flags, were added only for the synthetic demo version.

---

## Main KPI Terms

| KPI Term | Meaning | Type | Used in Analysis |
|---|---|---|---|
| Total Activation | Broad daily store activity measure representing total activation activity. | Activity count | Yes |
| New Activation | Daily count of new activation activity. | Activity count | Yes |
| Upgrade/SOR | Combined daily field for upgrades and sold-outright device activity. | Activity count | Yes |
| Account Gross | Dollar-based account gross measure from store performance reports. | Financial | Yes |
| Accessory Profit | Dollar-based accessory profit measure from store performance reports. | Financial | Yes |
| PPD | Broad monthly activity measure that includes new activations, reactivations, upgrades, sold-outright activity, and related device/service activity. | Activity count | Yes |
| Boxes | Devices sold from store inventory, such as phones or connected devices. | Activity count | Yes |
| New All | Total new monthly activation activity, including new voice and related non-phone service activity. | Activity count | Yes |
| New Voice | New phone or voice activation activity. | Activity count | Yes |
| Upg | Upgrade activity for existing customers or services. | Activity count | Yes |
| React | Reactivation activity for previously inactive or disconnected service. | Activity count | Yes |
| SOR | Sold outright activity, usually device sale without a new service activation. | Activity count | Yes |
| AAL | Add-a-line activity, meaning an additional line added to an account. | Activity count | Yes |
| Tablet | Tablet activation or tablet-related service activity. | Activity count | Yes |
| HINT | Home internet activation or home internet service activity. | Activity count | Yes |
| Watch | Smartwatch activation or watch-related service activity. | Activity count | Yes |
| Trade | Device trade-in count. | Activity count | Yes, reviewed carefully because of overlap |
| BTS | Bundle-related field that may overlap with tablet and home internet activity. | Activity count | Yes |
| Hours | Store operating hours. | Operational | Yes |
| Box/Hr | Activity or device movement relative to store operating hours. | Efficiency | Yes |
| QPAY | Bill payment activity count. | Activity count | Yes |
| Conv % | Conversion-style measure comparing activity volume with bill payment traffic. | Efficiency | Yes |
| Acc $ | Accessory revenue in dollars. | Financial | Yes |
| Acc Qty | Number of accessories sold. | Activity count | Yes |
| Acc/PPD | Accessory revenue per PPD activity. | Efficiency | Yes |
| Acc/Box | Accessory revenue per device sold. | Efficiency | Yes |
| Base MRC | Base monthly recurring charge value. | Financial | Yes |
| Feature Rev | Revenue from add-on features or extra services. | Financial | Yes |

---

## Synthetic Demo Fields

The following fields were added only for the public demo version. They are not presented as real company-provided fields.

| Field | Meaning | Type | Used in Analysis |
|---|---|---|---|
| Promotion Flag | Synthetic flag showing whether a promotion was active on a given day. | Synthetic demo feature | Demo only |
| Local Event Flag | Synthetic flag showing whether a local event was active on a given day. | Synthetic demo feature | Demo only |
| Inventory Issue Flag | Synthetic flag showing whether the store had an inventory issue on a given day. | Synthetic demo feature | Demo only |

---

## Notes for Interpretation

- Activity count fields show store activity volume, not revenue.
- Financial fields represent dollar-based performance measures.
- Efficiency fields compare performance relative to activity volume, device sales, or labor hours.
