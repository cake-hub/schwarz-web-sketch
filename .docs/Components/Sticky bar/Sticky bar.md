<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. [What can be modified](#what-can-be-modified)?
</AlertInfo>


# Sticky bar

This element indicates that the user is on a sub-brand page of SCHWARZ Enterprise. It also provides a "back-to-top" scrolling function.

It only exists in combination with our [footer](../Footer/Footer.md) and has a fixed order that must be followed at the end of each web page.

---

## Recommendations

- The sender badge of your sub-brand is available at [Schwarz brandmangement](mailto:brandmanagement@mail.schwarz).

---

## Elements

The sticky bar is built from the following elements:

1. Background
1. Sender badge
1. "to top" button

![footer complete LG](assets/structure@1x.png)

---

## Overall styling

- Text-style for the "to top"-button-text is always [small](../../General/Typography/Typography.md#small).
- The line height for the "to top"-button-text is **120%**.
- The background-color is always **brand-primary-base**.
- The icon is always "arrow-up.svg".


### States

- Only the "to top"-button has a hover/focus state.

| Types | Attributes | Preview |
|---|---|---|
| Default |  text-color: basic-white<br>icon-color: basic-white | ![button: default](assets/states/default@1x.png)|
| Hover / focus | text-color: gray-lighter<br>icon-color: gray-lighter| ![button: hover](assets/states/hover-focus@1x.png)|

---

## Position

- It always sticks at the bottom of the viewport as the user scrolls up or down the page.

---

## Spacing & measurements

- The background expands over the whole screen.
- The sender badge's height scales to the complete element height depending on the viewport.
- Lock the sender badge's ratio to scale it.

| Types | Attributes | Preview |
|---|---|---|
| Width | 1264px (LG)<br> 944px (MD)<br> 584px (SM)<br> 304px (XS) |![Width: LG](assets/measurements/width/LG@1x.png)<br>![Width: MD](assets/measurements/width/MD@1x.png)<br>![Width: SM](assets/measurements/width/SM@1x.png)<br>![Width: XS](assets/measurements/width/XS@1x.png)|
| Height | 32px (LG)<br> 24px (MD-XS) | ![Height: LG](assets/measurements/height/LG@1x.png)<br>![Height: MD-XS](assets/measurements/height/MD-XS@1x.png) |
| Horizontal spacing (LG) | padding-left: 80px <br> padding-right: 88px | ![Horizontal-spacing: LG](assets/measurements/horizontal-spacing/LG@1x.png) |
| Horizontal spacing (MD-XS) | padding-left: 0px<br>padding-right: 8px  |![Horizontal-spacing: MD-XS](assets/measurements/horizontal-spacing/MD-XS@1x.png) |
| Horizontal spacing (to top) | margin: 8px |![Horizontal-spacing: to top](assets/measurements/to-top@1x.png) |
| Vertical spacing | All elements are vertically centered  |![Vertical-spacing](assets/measurements/vertical-spacing@1x.png)|
| Icon size| 16 x 16px |![Icon-size](assets/measurements/icon-size@1x.png)|

---

## Example

 ![sticky bar: example](assets/example/sticky-bar-example.gif)

 ---

## What can be modified?

- Adjust the width of symbols according to the breakpoint.

### Our workflow in Sketch

- Use the „Overrides“-function to edit the button text and it's state.
