<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Tab bar

A bar appears at the bottom of the screen, allowing the user to quickly switch between different areas within an app.

---

## General information

- The complete symbol should contain at least 4 to a maximum of 5 items.
- The symbol is designed to only work in a single line scenario .

---

## Overall styling

- The text-style is **small**.
- The line-height is **120%**.
- The letter-spacing is **-0,2**.
- The icon size is **24x24px**.
- The divider comes in **gray-lighter** and has a **thickness of 1px**.
- The background-color always is **basic-white**.
- It uses the [badge-addon](Components/Badge/Badge.md#Addon) to display a counter (e.g. how many products are in the shopping cart or wishlist).

![tab bar](assets/elements/complete@1x.png)

---

## Elements

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker<br>icon-color: gray-darker | ![default](assets/elements/default@1x.png) |
| Active | text-color: brand-primary-base<br>icon-color: brand-primary-base | ![active](assets/elements/active@1x.png) |

---

## Spacing & Measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | icon: 24px<br>text: 4px  | ![horizontal-spacing](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 2px | ![vertical-spacing](assets/measurements/vertical-spacing@1x.png) |
| Alignment | horizontally centered | ![vertical-spacing](assets/measurements/vertical-alignment@1x.png) |
| Size | icon: 24x24px | ![icon-size](assets/measurements/icon-size@1x.png) |
| Height | fixed: 64px | ![height](assets/measurements/height@1x.png) |

---

## Position

| Types | Attributes | Preview |
|---|---|---|
| Addon | padding-right: 16px | ![addon-position](assets/position/addon@1x.png) |

---

## What can be modified?

- Override the text and icons.
- Adjust the width of single symbols according to the width of the device and the amount of used tab bar items.
