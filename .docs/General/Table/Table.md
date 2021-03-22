<AlertWarning alertHeadline="Not modifiable">
It is mandatory to maintain the appearance and behavior of these components.
</AlertWarning>

# Tables

Tables are texts in several columns and rows.

In our case, only rows are separated by a horizontal divider. The use of background colors is an additional distinction.

---

## Overall styling

- The text-style is [basic](../../General/Typography/Typography.md#basic) or [basic-bold](../../General/Typography/Typography.md#medium-condensed-basic-bold) for headlines.
- The line-height is set to **default**.
- The font-color is **basic-black** and for headlines **brand-primary-base**.
- Content dividers have **gray-lighter** as color and a **1px thickness**.
- Column header dividers have **brand-primary-base** as color but a **2px thickness**.
- The background-color for a table in zebra look is always **gray-lightest**, it stays in a **transparent** look if theres is no background-color desired.

---

## General

There are different kinds of tables.

### Simple table

- Just a simple table with no special styling or layout.

![Simple table](assets/styles/simple-table@1x.png)

### Table with headers

- Column-head differs visually in text-style and divider.
- Row-head differs visually in text-style.

![With headers](assets/styles/tables-with-headers@1x.png)

### Table with vertical background

- The background color changes in every odd column (e.g. 1, 3, 5, 7,…).

![Vertical background](assets/styles/table-with-vertical-background@1x.png)

### Table with horizontal background

- The background color changes in every odd row (e.g. 1, 3, 5, 7,…).

![Horizontal background](assets/styles/table-with-horizontal-background@1x.png)

---

## Special behavior

- The table can be scrolled **vertically** and **horizontally** for tables that are wider than the viewport.
- A **zoom function** can be added for smaller devices.
- The font size depends on the size of the body text.
- In some cases, a different font size can be used.

---

## Spacing & measurements

| Type | Attributes | Preview |
|---|---|---|
| Vertical spacing<br>(for _column head_, _row head_ & _table content_) | padding-top: 8px<br>padding-bottom: 8px | ![Vertical spacing: table content](assets/measurements/vertical-1@1x.png) |
| Horizontal spacing<br>(for _column head_, _row head_ & _table content_) | padding-left: 16px<br>padding-right: 16px | ![Horizontal spacing: table content](assets/measurements/horizontal-1@1x.png) |

---

## Our workflow in Sketch

- There are symbols in our library to layout tables.
- Each table must be created independently.
- The different „Overrides“-functions help here.
