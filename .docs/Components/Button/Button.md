<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Buttons

A button should lead the user to a certain action. Unique labels give the user a clear message which action is exactly triggered.

The actions can be separated into two buttons. The design of two different buttons shows the user a visual distinctions which action is needed to fulfill his task. Visually separating the primary and secondary buttons also helps to draw the attention of the user on a certain action.

---

## Recommendations

### Do's

- The secondary button can be used without the primary button.
- Keep the text short and use as few words as possible.
- Always use a specific call to action text.
- Choose a unique button labeling to send a clear message which action is exactly triggered by the button.
- Ensure consistent labelling across the user journey.
- Be sure to allow enough space for translation into other languages.
- A button with an icon may only be used in combination with an input field.

### Dont's

- Do not use more than two buttons below each other.
- Avoid exclamation marks.

**Hint!** You can use links as an alternative to a button to offer the secondary action.

---

## Types

- You can use different types of buttons: label, label with icon, icon.
- All devices have the same buttons sizes.
- Each button level is available in a positive and a negative version – this allows you to layout on a light or dark background.

### Primary

- Our primary button is also our Call-to-Action (CTA) button.
- It only should be used once per page.
- It gives the user a hint to fulfill his task.
- It's used to guide the user into taking certain actions.
- It usually invites users to sign in, register, purchase, etc.
- It is used to strongly suggest something that "we" want the user to do in first place.


| Version | Label| Label with icon | Icon |
|---|---|---|---|
| Positive | ![Primary](assets/types/positive/primary/label@1x.png) | ![Primary with icon](assets/types/positive/primary/with-icon@1x.png) | ![Primary icon](assets/types/positive/primary/icon@1x.png) |
| Negative | ![Negative](assets/types/negative/primary/label@1x.png) | ![Negative with icon](assets/types/negative/primary/with-icon@1x.png) | ![Negative icon](assets/types/negative/primary/icon@1x.png) |

### Secondary

- Use our secondary button if you want to show more than one button.
- It should only be used in conjunction with the primary button.
- It is offered to show the user a supporting task.
- It isn't as important and shouldn’t call as much attention as the Primary/CTA.
- Normally, secondary buttons can be used more than once per page.
- It offers users an alternative to the Primary/CTA (e.g. "back" instead of "next"; "add to wishlist" instead of "add to cart"; "edit", "delete", etc.).
- It leads the user away from his primary task or forwards to subpages of the website.

| Version | Label| Label with icon | Icon |
|---|---|---|---|
| Positive | ![Secondary](assets/types/positive/secondary/label@1x.png) | ![Secondary with icon](assets/types/positive/secondary/with-icon@1x.png) | ![Secondary icon](assets/types/positive/secondary/icon@1x.png) |
| Negative | ![Secondary](assets/types/negative/secondary/label@1x.png) | ![Secondary with icon](assets/types/negative/secondary/with-icon@1x.png) | ![Secondary icon](assets/types/negative/secondary/icon@1x.png) |


---

## Overall styling

- The text-style is **button-text**.
- All buttons have **rounded corners** with **2px radius**.
- Secondary buttons have a **outline** with a **1px thickness**.

### Positive

- Hover, focus & active states have an additional basic-black with **32% opacity** to the background.
- Disabled states have a background and font colors with **16% opacity**.

#### Primary

| State | Attributes | Preview |
|---|---|---|
| Default | background: brand-primary-base<br>text-color: basic-white | ![Primary default](assets/states/positive/primary/default@1x.png) |
| Hover, focus and active | background: brand-primary-base<br>_additional basic-black with 32% opacity_<br>text-color: basic-white | ![Primary hover, focus & active](assets/states/positive/primary/active@1x.png) |
| Disabled | background: brand-primary-base<br>_with 16% opacity_<br>text-color: brand-primary-base<br>_with 16% opacity_ | ![Primary disabled](assets/states/positive/primary/disabled@1x.png) |

#### Secondary

| Status | Attributes | Preview |
|---|---|---|
| Default | outline-color: brand-primary-base<br>text-color: brand-primary-base | ![Secondary default](assets/states/positive/secondary/default@1x.png) |
| Hover, focus and active | background: brand-primary-base<br>_additional basic-black with 32% opacity_<br>text-color: basic-white| ![Secondary hover, focus & active](assets/states/positive/secondary/active@1x.png) |
| Disabled | outline-color: brand-primary-base<br>_with 16% opacity_<br>text-color: brand-primary-base<br>_with 16% opacity_| ![Secondary disabled](assets/states/positive/secondary/disabled@1x.png) |

### Negative

- Hover, focus & active states have an additional gray-base with **32% opacity** to the background.
- Disabled states have a background and font colors with **16% opacity**.

#### Primary

| Status | Attributes | Preview |
|---|---|---|
| Default | background: basic-white<br>text-color: brand-primary-base | ![Primary default](assets/states/negative/primary/default@1x.png) |
| Hover, focus and active | background: basic-white<br>_additional gray-base with 32% opacity_<br> text-color: brand-primary-base | ![Primary hover, focus & active](assets/states/negative/primary/active@1x.png) |
| Disabled | background: basic-white<br>_with 16% opacity_<br>text-color: basic-white<br>_with 16% opacity_ | ![Primary disabled](assets/states/negative/primary/disabled@1x.png) |

#### Secondary

| Status | Attributes | Preview |
|---|---|---|
| Default | outline-color: basic-white <br>text-color: basic-white |  ![Secondary default](assets/states/negative/secondary/default@1x.png) |
| Hover, focus and active | background: basic-white<br>_additional gray-base with 32% opacity_<br>text-color: brand-primary-base | ![Secondary hover, focus & active](assets/states/negative/secondary/active@1x.png) |
| Disabled | outline-color: basic-white<br>_with 16% opacity_<br>text-color: basic-white<br>_with 16% opacity_ | ![Secondary disabled](assets/states/negative/secondary/disabled@1x.png)|

---

## Spacing & Measurements

| Type | Attributes | Preview |
|---|---|---|
| Horizontal | padding-left: 16px<br>padding-right: 16px<br>margin: 8px | ![button: padding](assets/measurements/horizontal-padding@1x.png) |
| Vertical | text is _vertically centered_ | ![button: padding](assets/measurements/vertical-padding@1x.png) |
| Height | 40px | ![button: height](assets/measurements/height@1x.png) |
| Distance  | 8px between two buttons | ![button: padding](assets/measurements/distance@1x.png) |
| Icon size | icon-size: 24x24px | ![button: icon-size](assets/measurements/icon-size@1x.png) |
