<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Ad-tag

Ad-tag component shows to the user that certain component is used for advertising purpose. It is part of legal requirements for advertisements.

---

## Overall styling

- The text-style is [small](/Lidl/Web/Design/General/Typography/Typography.md#small).
- The line-height is set to **default**.
- The color is set to **gray-darker**.

### Ad-tag

- The symbol has a general basic-white background for image advertisements.
- The background can be changed to the transparent background when it is placed below a component, e.g. recommendation slider.
- The ad-tag with transperency background works only on light backgrounds such as e.g gray-background.
- The expression exclamation-circle icon is **optional** and can trigger a modal view/sheet.
- The text-length is limited to a **single word** only.
- The whole area of ad-tag is interactive.

| Size | Attributes | Preview | Variants |
|---|---|---|---|
| MD-XS | text-color: gray-darker<br>icon-color: gray-darker<br>background-color: basic-white or transparent| ![ad-tag: default](assets/states/default-MD-XS@1x.png) |  ![ad-tag: variants](assets/states/default-MD-XS-variants@1x.png) |

---

## Spacing & measurements

- The ad-tag is placed on the top left area of the hero slider and is left aligned.

### Measurements

| Types | Attributes | Preview
|---|---|---|
| Horizontal spacing | padding: 4px | ![measurements: padding](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding-top: 0px<br> icon is vertical centered | ![measurements: padding](assets/measurements/vertical-spacing@1x.png) |
| Height | MD-XS: 17px | ![measurements: height](assets/measurements/height@1x.png) |
| Size | icon: 12x12px | ![measurements: icon size](assets/measurements/icon@1x.png) |


### Spacing

| Types | Attributes | Preview
|---|---|---|
| Spacing | minimum **4px** below components when ad-tag with transparent background is used <br>no other components should be placed in the same horizontal line | ![measurements: spacing transparent](assets/measurements/spacing-transparent@1x.png) |
| Spacing | 0px on hero slider images<br>position: top left  | ![measurements: spacing on image](assets/measurements/spacing-on-image@1x.png) |

---

## Examples

| Position | Preview |
|---|---|
| Hero slider ad | ![example: image](assets/example/image@1x.png) |
| Reco slider ad | ![example: reco slider](assets/example/reco-slider@1x.png) |
| Product tile ad| ![example: product tile](assets/example/product-tile@1x.png) |

---

### Our workflow in Sketch

- Use the "Overrides"-function to customize your ad-tag symbol (i.e. enter text, with-icon or none icon, choose background color).
