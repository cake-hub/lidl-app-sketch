<AlertWarning alertHeadline="Not modifiable">
 It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Coupon

Use this component if there is no possibility to display a specific product pricebox because the discount relates to a complete category or offer.

> Use it **only to promote LIDL Plus offers**  and only in combination with a **product tile, teaser or image**.

---

## Elements

| Attributes | Preview |
|---|---|
| 1. Discount <br> 2. Coupon text <br> 3. Legal info ("Lidl Plus price")| ![LIDL Plus coupon](assets/variants/coupon@1x.png) |

---

## Recommendations

- Keep the text short and **single line**.

---

## Overall styling

### Discount

- The text-style is [pricebox-small](/Lidl/Web/Design/General/General/Typography/Typography.md#pricebox-small).
- This element has **rounded corners of 2px** on the **upper left and right corner**.

| Attributes | Preview |
|---|---|
| text-color: basic-white <br> background-color: info-base | ![Discount: MD+SM](assets/styling/discount@1x.png) |

### Coupon text

- The text-style is [small](/Lidl/Web/Design/General/Typography/Typography.md#small).
- This element has **rounded corners of 2px** on the **lower left and right corner**.

| Attributes | Preview |
|---|---|
| text-color: basic-black <br> background-color: mark-base | ![Coupon text: MD+SM](assets/styling/coupon-text@1x.png) |

### Legal info

- The text-style is [pricebox-basic-quantity](/Lidl/Web/Design/General/Typography/Typography.md#pricebox-basic-quantity).
- This element follows the styling of our [positive link version](/Lidl/Web/Design/General/Link/Link.md#positive-version).
- Tapping on this info opens a bottom sheet that shows the Lidl Plus info text.

> The legal info is a required addon for the complete **LIDL Plus price** and has a fix notation of "Lidl Plus price".

| Attributes | Preview | Behavior |
|---|---|---|
| text-color: info-base | ![legal info: MD+SM](assets/styling/legal@1x.png) | ![behavior: bottom-sheet](assets/position/bottom-sheet@1x.png) <br> *This is a non-obligatory example.* |

---

## Spacing & measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | 4px | ![Horizontal spacing (LG)](assets/measurements/MD+SM/horizontal-spacing@1x.png) |
| Vertical spacing | padding-top: 18px / 10px (MD+SM / XS)<br>padding-bottom: 2px| ![Vertical spacing (MD+SM)](assets/measurements/MD+SM/vertical-spacing@1x.png) ![Vertical spacing (XS)](assets/measurements/XS/vertical-spacing@1x.png)|
| Height | 24px<br>Text horizontally centered | ![Height (MD-XS)](assets/measurements/MD-XS/height@1x.png) |
| Circle size | MD+SM: 32 x 16px <br> XS: 16 x 8px | ![Size: cut out (MD+SM)](assets/measurements/MD+SM/top@1x.png) ![Size: cut out (XS)](assets/measurements/XS/top@1x.png) |
| Distance | margin-top: 2px | ![Distance](assets/measurements/MD-XS/distance@1x.png)

---

## Position & combinations

- The coupon is placed in the **lower left corner** instead of a pricebox.
- The distance of the coupon to the borders of the product tile is **8px** each.

![position](assets/position/coupon@1x.png)

*This is a non-obligatory example.*
