<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Banner

The banner element is mainly used to create a focus  on a certain topic.

This focus is underlined with the help of a headline, text and image to give the user more information.

---

## Recommendations

- Keep the text short.
- The body text in our tablet portrait and smartphone components shouldn't be longer than a maximum of two lines.
- If the body text is longer than two lines it ends with ellipsis.

---

## Overall styling

- It has **no hover** or **focus** state.
- The headline uses the text-style **display 1**.
- The body-text comes in the text-style **basic**.
- The line-height of the display text-style is set to **100%**.
- There is **no inverted variant** for portrait tablet (SM) and smartphone (XS) breakpoints because the textual part always is placed under the image with a colored background.
- The picture is set to a **16:9** but can be adjusted to any preferred ratio.
- The text always is placed on the plain color and never on an image.

---

## Variants

- The banner is available in **default** and **inverted**.
- It's further clustered into **positive** and **negative**.


### Default

- The text is placed on the arrow element, the picture is situated behind it.

| Types | Attributes | Preview |
|---|---|---|
| Positive | text-color: basic-white<br>background-color: brand-primary-base | ![variants: default-positive](assets/variants/default/positive@1x.png) |
| Negative | text-color: brand-primary-base (headline), basic-black (text)<br>background-color: gray-lightest | ![variants: default-negative](assets/variants/default/negative@1x.png) |


### Inverted

- The picture is placed in the arrow element, the text stays on its background.


| Types | Attributes | Preview |
|---|---|---|
| Positive | text-color: basic-white<br>background-color: brand-primary-base | ![variants: inverted-positive](assets/variants/inverted/positive@1x.png) |
| Negative | text-color: brand-primary-base (headline), basic-black (text)<br>background-color: gray-lightest | ![variants: inverted-negative](assets/variants/inverted/negative@1x.png) |


---

## Possible adjustments

- This adjustments mainly concern the components with an arrow element.
- The peak of the arrow element can be positioned at any column of the grid but it always has to keep its defined angle.
- Please pay attention that the **colored area doesn't take more than 50%** of the layout.
- There should be **enough space** for the textual part as well.

![adjustment: arrow](assets/adjustments/arrow@1x.png)


---


## Spacing & Measurements

### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 112px / 146px (LG)<br>padding: 40px / 80px (MD)<br>padding: 16px (SM+XS)<br>*text is horizontally centered* | ![horizontal spacing: LG](assets/measurements/horizontal-spacing/LG@1x.png)<br>![horizontal spacing: MD](assets/measurements/horizontal-spacing/MD@1x.png)<br>![horizontal spacing: SM+XS](assets/measurements/horizontal-spacing/SM+XS@1x.png)  |
| Vertical spacing | margin-bottom: 8px (all breakpoints)<br>padding: 16px (SM+XS)| ![vertical spacing: SM+XS](assets/measurements/vertical-spacing/LG+MD@1x.png)<br>![vertical spacing: SM+XS](assets/measurements/vertical-spacing/SM+XS@1x.png) |


### Measurements

- The width of the symbol always adapts to the viewport – up to a maximum of 1920px.

| Types | Attributes | Preview |
|---|---|---|
| Height | Depends on the image ratio but is set to  9/16 of the image width<br>The textual section depends on the content but has a fixed padding| ![height: LG+MD](assets/measurements/height/LG+MD@1x.png)<br>![height: SM+XS](assets/measurements/height/SM+XS@1x.png) |
| Width | LG: 1280px (max. 1920px)<br>MD: 960px<br>SM: 600px<br>XS: 320px | ![width: LG](assets/measurements/width/LG@1x.png)<br>![width: MD](assets/measurements/width/MD@1x.png)<br>![width: SM](assets/measurements/width/SM@1x.png)<br>![width: XS](assets/measurements/width/XS@1x.png) |
| Angle | Outer angle: 26°<br>Inner angle: 128° | ![Angle](assets/measurements/angle@1x.png) |

---

## What can be modified?

- Override the text.
- Adjust the width of the arrow and picture.
