<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Alerts

Different types of notifications with contextual feedback about user actions as well as permanent presentation of important information.

---

## Recommendations

- **Keep the alerts text as short as possible. Especially the title.**
- Use an alert, i.e for feedback, recalls or support.
- Use links in the alert with caution. It might be more appropriate to link the entire alert instead of one word.

---

## Overall styling

- The text style is **large-bold** for the **title** and **basic** for the **text**.
- Every variant uses **basic-white** as background-color.
- The border has a **thickness of 1px**.
- The line-height for the "alert title" is **120%**, it stays **140%** for the "alert text".
- All widths are individually adjustable and fit into the layout columns and the 8-point-grid.
- The height depends on the content and the additional components shown.
- Every alert comes with the icon "cross.svg" as "close"-icon in the right upper corner.
- The color of the icon "cross.svg" stays the same in the focus/hover state. Only the cursor changes to pointer.

### Title & icon

- Some alerts come with an additional fixed icon to emphasize their meaning.

| Version | Attributes | Preview |
|---|---|---|
| primary | text-color: brand-primary-base<br>outline-color: brand-primary-base<br>icon-color: brand-primary-base<br>icon: information-circle.svg (currently placeholder.svg) | ![primary](assets/with-title/primary@1x.png) |
| info | text-color: brand-info-darker<br>outline-color: brand-info-base<br>icon-color: brand-info-darker<br>fixed icon: information-circle.svg | ![info](assets/with-title/info@1x.png) |
| danger | text-color: danger-darker<br>outline-color: danger-base<br>icon-color: danger-darker<br>fixed icon: exclamation-triangle.svg | ![danger](assets/with-title/danger@1x.png) |
| success | text-color: success-darker<br>outline-color: success-base<br>icon-color: success-darker<br>fixed icon: hook-circle.svg | ![success](assets/with-title/success@1x.png) |
| gray / neutral | text-color: basic-black<br>outline-color: gray-dark<br>icon-color: basic-black<br>icon: not fix (currently placeholder.svg) | ![gray-neutral](assets/with-title/gray-neutral@1x.png) |

### Text

- Simple alerts to only display text.

| Version | Attributes | Preview |
|---|---|---|
| primary | text-color: brand-primary-base<br>icon-color: brand-primary-base<br>outline-color: brand-primary-base | ![primary](assets/text/primary@1x.png) |
| info | text-color: brand-info-darker<br>icon-color: brand-info-darker<br>outline-color: brand-info-base | ![info](assets/text/info@1x.png) |
| danger | text-color: danger-darker<br>icon-color: danger-darker<br>outline-color: danger-base | ![danger](assets/text/danger@1x.png) |
| success | text-color: success-darker<br>icon-color: success-darker<br>outline-color: success-base | ![success](assets/text/success@1x.png) |
| gray / neutral | text-color: basic-black<br>icon-color: basic-black<br>outline-color: gray-dark | ![gray-neutral](assets/text/gray-neutral@1x.png) |

---

## Link

Some alerts use links to direct the user to another page.

- Every variant uses the **basic-white** as **text-color**.
- In the default/hover/focus state the **text-decoration** is **underline**.

| State | Attributes | Preview |
|---|---|---|
| Default / visited |  | ![alert link default](assets/link/default-hover/primary@1x.png) |
| Hover / focus | cursor: changes to pointer  | ![alert link hover](assets/link/default-hover/primary@1x.png) |
| Active / pressed | text-decoration: none | ![alert link active](assets/link/active-pressed/primary@1x.png) |

---

## Spacing & Measurements

| Types | Attributes | Preview |
|---|---|---|
| Horizontal spacing | padding: 16px | ![Horizontal spacing](assets/measurements/horizontal-spacing@1x.png) |
| Vertical spacing | padding: 16px<br>margin-bottom: 8px | ![Vertical spacing](assets/measurements/vertical-spacing@1x.png) |
| Icon size | meaning: 32x32px<br>close: 16x16px | ![Icon size](assets/measurements/icon-size@1x.png) |

---

## What can be modified?

- Override the text and icons.
- Adjust the width and height according to the content.
- Modify alerts to your project needs by adding other symbols or styles (i.e. like dividers or links).

### Our workflow in Sketch

- Use the „Overrides“-function to select the required variant, to edit the content, to change the icon if necessary or if the alert can’t be closed.
