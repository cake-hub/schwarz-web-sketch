<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Frame

The corner component belongs - like [bubble](../Bubble/Bubble.md), [corner](../Corner/Corner.md) and [marker](../Marker/Marker.md) - to the group of **flashes**.

Use the different flashes to emphasize messages with a strong meaning.

---

## Recommendations

- All flash elements should be used sparingly to avoid overload.
- Please use the corner only for a maximum text length of two lines.

---

## Overall styling

- The frame has **no hover-** and **focus-state**.
- The text-style depends on the component but is always **bold**.
- The line-height always is **120%**.

---

## Variants

- The frame element is available in different colors, which are subcategorized into: **positive** and **negative**
- There is an additional separation into **left** and **right** due to the positioning of the symbol.

| Types | Attributes | Preview |
|---|---|---|
| Primary (positive) | text-color: basic-white<br>background-color: brand-primary-base | ![left: primary](assets/types/primary@1x.png) |
| Secondary (positive) | text-color: basic-white<br>background-color: brand-secondary-base | ![left: secondary](assets/types/secondary@1x.png)|
| Info (positive) | text-color: basic-white<br>background-color: brand-info-darker | ![left: info](assets/types/info@1x.png) |
| Attention (negative) | text-color: basic-black<br>background-color: brand-attention-base | ![left: attention](assets/types/attention@1x.png) |

---

### Position

- The frame symbol can either be placed on the **left** or **right** side of a component.
- The correct position is determined by the symbol name.

![position](assets/position/frame@1x.png)



---

### Spacing & Measurements

- The width of the corner component depends on the content.

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px / 8px (left)<br>padding: 8px / 16px (right) | ![horizontal-spacing](assets/measurements/horizontal-spacing@1x.png)|
| Vertical spacing | the text is always optically vertically centered | ![vertical-spacing](assets/measurements/vertical-spacing@1x.png) |
| Height | LG: 64px<br>MD-XS: 56px  | ![Height](assets/measurements/height@1x.png) |
| Angle | inner angle: 64° | ![rotation](assets/measurements/angle@1x.png)


---

## What can be modified?

- Override the text.

### Our workflow in Sketch

- Use the "Overrides"-function to change the text.
- Use the "Overrides"-function to change the background-color via layer-styles (this is only available in the positive variant).
- The width of the symbol has to be adjusted manually.