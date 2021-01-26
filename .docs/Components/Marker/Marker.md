<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Marker

The marker component belongs - like [bubble](../Bubble/Bubble.md), [corner](../Corner/Corner.md) and [frame](../Frame/Frame.md) - to the group of **flashes**.

Use the different flashes to emphasize messages with a strong meaning.

---

## Recommendations

- All flash elements should be used sparingly to avoid overload.
- Please use the marker only for a maximum text length of one to four lines.

---

## Overall styling

- The marker has **no hover-** or **focus-state**.
- The text-style depends on the component and is always **bold**.
- The line-height is always **120%**.

---

## Variants

- The marker element is available in different sizes, depending on the corresponding text-styles: **small-**, **basic-** and **large-bold**
- Please use the marker that corresponds to the breakpoint, as there are different sizes available: **small**, **basic**, **large**.
- The marker element is available in different colors, which are subcategorized into: **positive** and **negative**.

| Types | Attributes | Preview |
|---|---|---|
| Primary (positive) | text-color: basic-white<br>background-color: brand-primary-base | ![primary](assets/types/primary@1x.png) |
| Secondary (positive) | text-color: basic-white<br>background-color: brand-secondary-base | ![secondary](assets/types/secondary@1x.png)|
| Info (positive) | text-color: basic-white<br>background-color: brand-info-darker | ![info](assets/types/info@1x.png) |
| Attention (negative) | text-color: basic-black<br>background-color: brand-attention-base | ![attention](assets/types/attention@1x.png) |

---

### Position

- The marker element can be placed completely free in the layout.

![position](assets/position/marker@1x.png)


---

### Spacing & Measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | 8px | ![horizontal-spacing](assets/measurements/horizontal-spacing@1x.png)|
| Vertical spacing | the text is always vertically centered | ![vertical-spacing](assets/measurements/vertical-spacing@1x.png) |
| Height (LG) | small: 36px<br>basic: 40px<br>large: 44px  | ![sizes: LG](assets/measurements/height/LG@1x.png) |
| Height (MD-XS) | small: 32px<br>basic: 36px<br>large: 40px  | ![sizes: MD-XS](assets/measurements/height/MD-XS@1x.png) |
| Width (LG) | small: 96px<br>basic: 136px<br>large: 176px  | ![sizes: LG](assets/measurements/width/LG@1x.png) |
| Width (MD-XS) | small: 80px<br>basic: 120px<br>large: 160px  | ![sizes: MD-XS](assets/measurements/width/MD-XS@1x.png) |
| Angle | inner angle: 128°<br>outer angle: 26° | ![angle](assets/measurements/angle@1x.png)


---

## What can be modified?

- Override the text.

### Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Use the "Overrides"-function to change the background-color via layer-styles (this is only available in the positive variant).
