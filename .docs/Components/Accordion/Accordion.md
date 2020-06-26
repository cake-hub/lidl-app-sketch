<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Accordion

Use an accordion to manage a large amount of content through dynamic switching.

Parts of the content are hidden in a container and only displayed by the user's action.

---

## Overall styling

- The text-style is **basic**.
- The outline has a **1px thickness**.


### Accordion

- The symbol has rounded corners with a **2px** radius.
- The default state uses **"arrow-down"** and the focus/open state use **"arrow-up"** as an icon.

| States | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-darker<br>outline-color: gray-base<br>icon-color: gray-darker<br>background-color: basic-white | ![accordion: default](assets/states/default@1x.png) |
| Hover | text-color: gray-darker<br>outline-color: brand-primary-base<br>icon-color: gray-darker<br>background-color: basic-white | ![accordion: hover](assets/states/hover@1x.png) |
| Focus | text-color: brand-primary-base<br>outline-color: brand-primary-base<br>icon-color: gray-darker<br>background-color: basic-white | ![accordion: focus](assets/states/focus@1x.png) |
| Opened | text-color: brand-primary-base<br>outline-color: brand-primary-base<br>icon-color: gray-darker<br>background-color: basic-white | ![accordion: opened](assets/states/opened@1x.png) |
| Disabled | text-color: gray-base<br>outline-color: gray-light<br>icon-color: gray-base<br>background-color: gray-background | ![accordion: disabled](assets/states/disabled@1x.png) |

### Content

- The symbol has rounded corners with a **2px** radius on the **lower-left** and **-right** corner.

| States | Attributes | Preview |
|---|---|---|
| Opened | outline-color: brand-primary-base<br>background-color: basic-white | ![content: open](assets/content/open@1x.png) |

---

## Spacing & Measurements

- Width depends on device and usage.
- Only the height for the content symbol is free adjustable.

### Measurements

| Types | Attributes | Preview
|---|---|---|
| Horizontal spacing | padding: 16px<br>margin: 16px | ![measurements: padding](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding-top: 8px<br>padding-bottom: 16px | ![measurements: padding](assets/measurements/vertical-spacing@1x.png) |
| Height | 48px | ![measurements: padding](assets/measurements/height@1x.png) |
| Size | icon: 24x24px | ![measurements: padding](assets/measurements/icon@1x.png) |

### Spacing

| Types | Attributes | Preview
|---|---|---|
| Spacing | 8px between different components<br>content opens downwards | ![measurements: spacing](assets/measurements/spacing@1x.png) |

---

## What can be modified?

- Override the text.
- Adjust the width.
- Adjust the height but only for the "content" symbol.
- Modify the complete look of the symbol but please stick to the colors of the given states.

### Our workflow in Sketch

- Use the "Overrides"-function to customize your accordion element (i.e. select the correct status you want to display).
- Place the "content" symbol directly under the accordion to display an open status.
