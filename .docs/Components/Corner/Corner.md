<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Corner

The corner component belongs - like [bubble](../Bubble/bubble.md), [frame](../Frame/Frame.md) and [marker](../Marker/Marker.md) - to the group of **flashes**.

Use the different flashes to emphasize messages with a strong meaning.

---

## Recommendations

- All flash elements should be used sparingly to avoid overload.
- Please use the corner only for a single line text or just for one word.

---

## Overall styling

- The corner has **no hover-** or **focus-state**.
- The text-style depends on the component and is always **bold**.
- The line-height is always **120%**.

---

## Variants

- The corner element is available in different sizes, depending on the corresponding text-styles: **small-**, **basic-** and **large-bold**
- Please use the corner that corresponds to the breakpoint, as there are different sizes available: **small**, **basic**, **large**.
- The corner element is available in different colors, which are subcategorized into: **positive** and **negative**
- There is an additional separation into **top** and **bottom** due to the readability of the text.

### Top

| Types | Attributes | Preview |
|---|---|---|
| Primary (positive) | text-color: basic-white<br>background-color: brand-primary-base | ![top: primary](assets/types/primary/top@1x.png) |
| Secondary (positive) | text-color: basic-white<br>background-color: brand-secondary-base | ![top: secondary](assets/types/secondary/top@1x.png)|
| Info (positive) | text-color: basic-white<br>background-color: brand-info-darker | ![top: info](assets/types/info/top@1x.png) |
| Attention (negative) | text-color: basic-black<br>background-color: brand-attention-base | ![top: attention](assets/types/attention/top@1x.png) |

### Bottom

| Types | Attributes | Preview |
|---|---|---|
| Primary (positive) | text-color: basic-white<br>background-color: brand-primary-base | ![bottom: primary](assets/types/primary/bottom@1x.png) |
| Secondary (positive) | text-color: basic-white<br>background-color: brand-secondary-base | ![bottom: secondary](assets/types/secondary/bottom@1x.png)|
| Info (positive) | text-color: basic-white<br>background-color: brand-info-darker | ![bottom: info](assets/types/info/bottom@1x.png) |
| Attention (negative) | text-color: basic-black<br>background-color: brand-attention-base | ![bottom: attention](assets/types/attention/bottom@1x.png) |

---

### Position

| Types | Attributes | Preview |
|---|---|---|
| Top | This symbol has to be placed in the **top-left** or **-right** corner of any component. | ![position](assets/position/corner/top@1x.png) |
| Bottom | This symbol has to be placed in the **bottom-left** or **-right** corner of any component. | ![position](assets/position/corner/bottom@1x.png) |


---

### Spacing & Measurements

- The width of the corner component depends on the content.

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 8px | ![horizontal-spacing](assets/measurements/horizontal-spacing@1x.png)|
| Vertical spacing | the text is always vertically centered | ![vertical-spacing](assets/measurements/vertical-spacing@1x.png) |
| Height (LG) | small: 28px<br>basic: 36px<br>large: 44px  | ![sizes: LG](assets/measurements/height/LG@1x.png) |
| Height (MD-XS) | small: 24px<br>basic: 32px<br>large: 40px  | ![sizes: MD-XS](assets/measurements/height/MD-XS@1x.png) |
| Angle | inner angle: 45° | ![rotation](assets/measurements/angle@1x.png)


---

## What can be modified?

- Override the text.

### Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Use the "Overrides"-function to change the background-color via layer-styles (this is only available in the positive variant).
- The symbol has to be rotated by 45 degrees for the desired position.
