****<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. What can be modified can be found [here](#what-can-be-modified)
</AlertInfo>

# Rating

The product rating is visually represented with a star rating.

---

## Recommendations

- The maximum number of 5 stars can be reached.
- If the product has not yet been rated, no stars will appear.
- The number in the bracket indicates how many users have already submitted a rating.

---

## Elements

The rating component consists of:

![rating-element](assets/rating/elements@1x.png)

1. Stars
2. Rating number

---

## Overall styling

- The text style is [basic](../../../../Web/Design/General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- The icon **star-fill** or **star-percentage** is used.

Types | State | Attributes | Preview
---------| ---------|----------|---------
star | default | background-color: gray-light | ![rating-default](assets/states/star-default@1x.png)
star | hover-focus | background-color: gray-lighter | ![rating-default](assets/states/star-default-hover-focus@1x.png)
star-selected | default | background-color: mark-darker  | ![rating-selected](assets/states/star-selected@1x.png)
star-selected | hover-focus | background-color: mark-dark | ![rating-hover-focus](assets/states/star-hover-focus@1x.png)
component with stars | default| star background-color: gray-light<br> rating number color: brand-primary-base| ![rating default](assets/rating@1x.png)
component with stars | hover-focus | star background-color: gray-lighter <br> rating number color: brand-primary-darker | ![rating hover-focus](assets/rating/star-1/interactive/hover-focus@1x.png)
component with stars-selected | default| star background-color: gray-light<br>star-selected background-color: mark-darker<br> rating number color: brand-primary-base| ![rating default](assets/rating-selected@1x.png)
component with stars-selected | hover-focus | star background-color: gray-lighter <br>star-selected background-color: mark-dark<br> rating number color brand-primary-darker| ![rating hover-focus](assets/rating/star-1/interactive/selected-hover-focus@1x.png)

---

## Spacing & measurements

- The height of the rating is **16px**.
- The width depends on the number of given ratings in the bracket.

| Types | Attributes | Preview |
|---|---|---|
| Icon-size | 16px | ![icon-size](assets/measurements/star-size@1x.png) |
| Padding | 4px| ![padding](assets/measurements/padding@1x.png) |

---

## Behavior

The inside of the last star item can be filled from left to right based on percentages.
A rating can be interactive (e.g. on product detail page) or static (e.g. on product tile). If the rating is static the rating component has **no hover-focus state**.

---

## Variants

| Rating |  Preview |
|---|---|
| 5 stars |![star 5](assets/rating/star-5@1x.png)|
| 4 stars |![star 4](assets/rating/star-4@1x.png)|
| 3 stars |![star 3](assets/rating/star-3@1x.png)|
| 2 stars |![star 2](assets/rating/star-2@1x.png)|
| 1 stars |![star 1](assets/rating/star-1@1x.png)|
| No stars | Not yet rated - no stars are shown. |

---

## Examples

 This is a non-obligatory example of the positioning of the star rating on the product tile.

![position](assets/example-rating@1x.png)

---

## Our workflow in Sketch

- Use the "Overrides"-function to change the number of stars.

---

## References

> [T16 | Global] Rating Stars
