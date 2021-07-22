<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>


# Footer

Use the footer to help the customer with additional information and navigation at the bottom of a website.

It only exists in combination with our [sticky bar](../Sticky%20bar/Sticky%20bar.md) and has a fixed order that must be followed at the end of each web page.

---

## Recommendations

- Keep the footer as short as possible. Do not load it with unnecessary information. The customer is interested in a first glance.
- Ideally, important links will be opened via a new window or a tab in the browser.

---

## Elements

The default footer contains the following elements:

1. Headline
1. Main-Navigation
1. Divider
1. Meta-Navigation
1. Background

![footer complete LG](assets/complete/LG@1x.png)

### Usage of elements

| Headline | Main-Navigation | Meta-Navigation |
|---|---|---|
|This element is not absolutely necessary for the setup of a footer, unless you want to title or organize your main-navigation categories.|Use it to show a summary of all possible links or menus on a SCHWARZ website (i.e. sitemap, wishlist, shopping cart, account, ...).|For information, such as legal (imprint, terms and conditions, data protection, ...) or contact, which must be placed on a website.|

---

## Overall styling

- The background-color always is **gray-dark**.
- The divider width depends on the breakpoint but always has a **height of 1px** and the color **gray-base**.
- The line-height is set to **default**.

### Default

| Types | Attributes | Preview |
|---|---|---|
| Headline | text-style: [headline 5](../../General/Typography/Typography.md#headlines-headline-level-5)<br>text-color: gray-lighter | ![headline: default](assets/elements/headline/default@1x.png) |
| Main-Navigation | text-style: [basic](../../General/Typography/Typography.md#basic)<br>text-color: gray-lighter | ![main-nav: default](assets/elements/main-nav/default@1x.png) |
| Meta-Navigation | text-style: [basic](../../General/Typography/Typography.md#basic)<br>text-color: gray-lighter | ![meta-nav: default](assets/elements/meta-nav/default@1x.png)|

### Hover, focus, active

| Types | Attributes | Preview |
|---|---|---|
| Headline | For this element there is **no hover, focus, active** status. | --- |
| Main-Navigation | text-color: basic-white<br>text gets underlined | ![main-nav: hover](assets/elements/main-nav/hover@1x.png)|
| Meta-Navigation | text-color: basic-white<br>text gets underlined |![meta-nav: hover](assets/elements/meta-nav/hover@1x.png)|

---

## Spacing & measurements

### Complete

- The background expands over the whole screen.

| Types | Attributes | Preview |
|---|---|---|
| Width | 1264px (LG)<br> 944px (MD)<br> 584px (SM)<br> 304px (XS) |![Width: LG](assets/measurements/width/LG@1x.png)<br>![Width: MD](assets/measurements/width/MD@1x.png)<br>![Width: SM](assets/measurements/width/SM@1x.png)<br>![Width: XS](assets/measurements/width/XS@1x.png)|
| Horizontal spacing | padding-top/-bottom: 32px<br>margin: 16px |![Horizontal-spacing](assets/measurements/complete/horizontal-spacing@1x.png)|
| Vertical spacing | 8px |![Vertical-spacing](assets/measurements/complete/vertical-spacing@1x.png)|

### Elements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 8px | ![Horizontal-spacing: headline](assets/measurements/headline/horizontal-spacing@1x.png)<br>![Vertical-spacing: main-nav](assets/measurements/main-nav/horizontal-spacing@1x.png)<br>![Horizontal-spacing: meta-nav](assets/measurements/meta-nav/horizontal-spacing@1x.png) |
| Vertical spacing | the text gets horizontally centered | ![Vertical-spacing: headline](assets/measurements/headline/vertical-spacing@1x.png)<br>![Vertical-spacing: main-nav](assets/measurements/main-nav/vertical-spacing@1x.png)<br>![Vertical-spacing: meta-nav](assets/measurements/meta-nav/vertical-spacing@1x.png) |


---

## Variants

- Alternatively, the footer can be arranged in columns instead of rows.
- This happens only for the desktop and tablet (landscape) breakpoint and if there are 3 rows or more in the main-navigation.
- The main-navigation always extends over 2 columns including gutter and can add itself infinitely downwards.

| 3 columns | 4 colums |
|---|---|
|![footer: 3 cols](assets/variants/LG/3cols@1x.png)|![footer: 4 cols](assets/variants/LG/4cols@1x.png)|

---

## Example

 ![sticky bar: example](assets/example/sticky-bar-example.gif)

 ---

## What can be modified?

- Override the text.
- Adjust the width of single symbols according to the text.
- Add rows or columns.
- Switch between the two possible layouts (vertically or horizontally).
- Modify footers for your project needs by adding other symbols (i.e. input fields, badges, buttons, …).

### Our workflow in Sketch

- Use the „Overrides“-function to edit the content of the symbols:
  - main-navigation
  - meta-navigation
  - headline
