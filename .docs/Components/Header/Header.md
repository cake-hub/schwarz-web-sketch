<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>


# Header

The header is one of the essential components to create brand awareness.

The appearance demonstrates visitors that they are on a SCHWARZ page now. Its strongest supporting element is the SCHWARZ enterprise logo.

---

## Recommendations

- Keep the globally known SCHWARZ enterprise logo in the header.
- Try to display all navigation items with one short and concise keyword.
- Don't show more than five user-navigation elements (including the search icon in desktop and tablet).
- Please implement a search-function icon as the first user-navigation element from the right.


---

## Elements

- The structure of the header is **modular**.
- It is a group of symbols and typography from the SCHWARZ Fundamentals and SCHWARZ Web Kit.
- If you combine the individual elements in Sketch, you get the header in various forms and for each breakpoint.
- There is a **collapsed on-scroll layout** for our desktop and tablet (landscape) breakpoints.
- There is a separate header layout for tablets (portrait) and smartphones that opens a dropdown menu with the main- and sub-navigation over a burger-menu icon.
- The header contains the **logo**, **typography: main-, sub-, brand-** and **user-navigation**, as well as **colors** and **shadows**.

### Desktop & tablet landscape (LG & MD)

#### Extended

![Extended: LG+MD](assets/elements/LG+MD/extended@1x.png)

#### Collapsed: Main

![Collapsed: LG+MD - Main](assets/elements/LG+MD/collapsed-main@1x.png)

#### Collapsed: Sub

![Collapsed: LG+MD - Sub](assets/elements/LG+MD/collapsed-sub@1x.png)

1. Logo
1. Brand-navigation
1. Language
1. User-navigation
1. With integrated search
1. Main-navigation
1. Sub-navigation

### Tablet portrait & smartphone (SM & XS)

![Complete: SM+XS](assets/elements/SM+XS/complete@1x.png)

1. Logo
1. User-navigation
1. Burger-menu
1. Overlay
1. Search field (if it exists)
1. Main-navigation
1. Sub-navigation
1. Brand-navigation
1. Language
1. Dividers
1. Flyout

---

## Overall styling

- The **letter spacing** of every character is **0.2px**.
- The line-height of every text is **120%**.
- The header comes with a background-color in **basic-white**.
- It uses the **shadow-default**.
- The dividers in tablets (portrait) and smartphones have a **1px thickness** and use **gray-lightest** as color.
- The sub-navigation is positioned on the websites background but belongs to the complete header component.
- The search-field uses our [input-field](../Form/Form.md#input-field) states with the **"magnifier.svg"** as icon.
- Every text is **horizontally** aligned to the height.


---

## Logo

- The Logo comes in different sizes depending on:
  - the device
  - the extended or collapsed (on-scroll) mode for desktop and tablet (landscape).
- It is placed on a supporting area in **basic-white** that uses the **shadow-default**.
- Please regard the [logo extension](../../General/Logo/Logo.md#extension) description because of the logos position close to the screen border.

![Example: logo](assets/logo/example@1x.png)

---

## Brand-navigation

- Some SCHWARZ sub-brands have special pages to present their company (e.g. Twogo, Dieter Schwarz Stiftung, …).
- The text-style is [small](../../General/Typography/Typography.md#small).
- The indicator is displayed only in the **hover/focus** state.
- The **length** of the indicator is based on the **entered text**.
- A click on this navigation item opens a new tab in the user's browser.

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark |![brand: default](assets/brand/default@1x.png)|
| Hover / focus | text-color: basic-black<br>indicator: basic-black |![brand: hover/focus](assets/brand/hover-focus@1x.png) |

---

## Language

- This selection is required by countries that offer a SCHWARZ sub-brand website in different languages.
- The text-style is [small](../../General/Typography/Typography.md#small).
- The default state always shows the current language. It changes to another language after a new selection.

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark |![language: default](assets/language/default@1x.png)|
| Hover / focus | text-color: basic-black<br>indicator: basic-black |![language: hover-focus](assets/language/hover-focus@1x.png)|

---

## Main- & sub-navigation

- There are different types of usage for each section of the navigation.
- Use the main-navigation for main topics that the SCHWARZ sub-brand has to offer.
- Use the sub-navigation if a main topic has subitems.
- The sub-navigation is only displayed if the main-navigation is active.
- The indicator is displayed in a **different color** for the **hover/focus** or **active** state.
- The **length** of the indicator is based on the **entered text**.
- Its position is at the bottom of the element.


### Overall styling (LG & MD)

- The text-style for main-navigation is [basic](../../General/Typography/Typography.md#basic).
- The line-height is set to **default**.

### Extended

- The text-style for sub-navigation is [small](../../General/Typography/Typography.md#small).

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark | ![Extended: default (LG+MD)](assets/main+sub/LG+MD/extended/default@1x.png) |
| Hover / focus | text-color: basic-black<br>indicator: basic-black | ![Extended: hover-focus (LG+MD)](assets/main+sub/LG+MD/extended/hover-focus@1x.png) |
| Active | text-color: brand-primary-base<br>indicator: brand-primary-base | ![Extended: active (LG+MD)](assets/main+sub/LG+MD/extended/active@1x.png) |

### Collapsed

- The text-style for sub-navigation changes to [basic](../../General/Typography/Typography.md#basic).

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark | ![Collapsed: default (LG+MD)](assets/main+sub/LG+MD/collapsed/default@1x.png) |
| Hover / focus | text-color: basic-black<br>indicator: basic-black | ![Collapsed: hover-focus (LG+MD)](assets/main+sub/LG+MD/collapsed/hover-focus@1x.png) |
| Active | text-color: brand-primary-base<br>indicator: brand-primary-base | ![Collapsed: active (LG+MD)](assets/main+sub/LG+MD/collapsed/active@1x.png) |


### Overall styling (SM & XS)

- The text-style for main-navigation is [basic](../../General/Typography/Typography.md#basic).
- The text-style for sub-navigation is [small](../../General/Typography/Typography.md#small).
- The line-height is set to **default**.
- The **length** of the indicator starts at beginning of the component.
- Its position is at the bottom of the element.

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark | ![default (SM/XS)](assets/main+sub/SM+XS/default@1x.png)|
| Hover / focus | text-color: basic-black<br>indicator: basic-black | ![hover/focus (SM/XS)](assets/main+sub/SM+XS/hover-focus@1x.png) |
| Active | text-color: brand-primary-base<br>indicator: brand-primary-base | ![active (SM/XS)](assets/main+sub/SM+XS/active@1x.png)  |

---

## User-navigation

- This area is for user guidance with the support of icons.
- The most important elements for the user should be placed here (e.g. login, account, search …).
- It uses the [badge-addon](../Badge/Badge.md#addon) to display a counter.

| Types | Attributes | Preview |
|---|---|---|
| Default / active | icon-color: gray-dark | ![User-Nav: default/active](assets/user/default-active@1x.png) |
| Hover / focus | icon-color: basic-black | ![User-Nav: hover/focus](assets/user/hover-focus@1x.png) |

---

## Burger-menu

- Use this element only for tablets (portrait) and smartphones to demonstrate all navigation elements.
- In contrast to the user-navigation, a **"menu"-text** is shown.
- The text-style is always [small](../../General/Typography/Typography.md#small).
- It uses our **"bars-horizontal.svg"** icon to display a burger-menu.
- The burger changes to our **"cross.svg"** icon as a close-function.

| Types | Attributes | Preview |
|---|---|---|
| Default | text-color: gray-dark<br>icon-color: gray-dark | ![Burger-Menu: default](assets/burger/default@1x.png) |
| Hover / focus | text-color: basic-black<br>icon-color: basic-black | ![Burger-Nav: hover/focus](assets/burger/hover-focus@1x.png) |
| Active | text-color: gray-dark<br>icon-color: gray-dark | ![Burger-Menu: default](assets/burger/active@1x.png) |

---

## Flyout

- The main-navigation and language selection on desktop and tablet (landscape) show a flyout **on hover** with all possible options.
- It comes with a background-color of **basic-white**.
- It uses **shadow-default**.
- It is located directly under the indicator of the hover state.

| Types | Attributes | Preview |
|--|---|---|
| Default | text-color: gray-dark | ![Flyout: default](assets/flyout/default@1x.png) |
| Hover/focus | text-color: basic-black<br>indicator: basic-black | ![Flyout: hover/focus](assets/flyout/hover-focus@1x.png) |

---

## Spacing & measurements

- This section shows the different spacings of the desktop, tablet and mobile elements included in the header.


### Desktop & tablet landscape (LG & MD)

- All the spacing for these breakpoints and extended or collapsed mode are identical.
- Only the **height** and **width** of the used components are different.

#### Spacing

| Types | Attributes | Preview |
|---|---|---|
| Content | padding-left/-right: 8px | ![Content (LG+MD)](assets/spacing/LG+MD/content@1x.png) |
| Brand-navigation | padding-left/-right: 16px (8+8)<br>margin-right: 40px (8+24+8) / (8+16+16) | ![Brand-Nav (LG+MD)](assets/spacing/LG+MD/brand-navigation@1x.png) |
| User-navigation | padding: 32px (16+16) | ![User-Nav (LG+MD)](assets/spacing/LG+MD/user-navigation@1x.png) |
| Main-navigation | offset: 24px (16+8)<br>padding: 16px (8+8) | ![Main-Nav (LG+MD)](assets/spacing/LG+MD/main-navigation@1x.png) |
| Sub-navigation | offset: 24px (16+8)<br>padding: 16px (8+8) | ![Sub-Nav (LG+MD)](assets/spacing/LG+MD/sub-navigation@1x.png) |
| Flyout | padding: 8px | ![Flyout (LG+MD)](assets/spacing/LG+MD/flyout@1x.png)

#### Measurements

##### Extended

| Types | Attributes (LG / MD) | Preview |
|---|---|---|
| Height | complete: 159px / 130px<br>upper-section: 72px / 56px<br>main-navigation: 48px / 40px<br>sub-navigation: 40px / 24px<br>| ![Height  (LG)](assets/measurements/LG/extended/height@1x.png)<br>![Height (MD)](assets/measurements/MD/extended/height@1x.png) |
| Width | complete: 1280px / 960px | ![Width (LG)](assets/measurements/LG/extended/width@1x.png)<br>![Width (MD)](assets/measurements/MD/extended/width@1x.png) |
| Logo | size: 120x147px / 98x120px<br>extension: 12px / 10px | ![Logo (LG)](assets/measurements/LG/extended/logo@1x.png)![Logo (MD)](assets/measurements/MD/extended/logo@1x.png) |
| Brand-navigation | padding: 8px<br>height: 72px / 56px<br>margin-bottom: 4px<br>indicator: 1px  | ![Brand-nav (LG)](assets/measurements/LG/extended/brand-nav@1x.png)![Brand-nav (MD)](assets/measurements/MD/extended/brand-nav@1x.png)|
| Language | padding: 8px<br>height: 72px / 56px<br>margin-bottom: 4px<br>indicator: 1px | ![Language (LG)](assets/measurements/LG/extended/language@1x.png)![Language (MD)](assets/measurements/MD/extended/language@1x.png) |
| User-navigation | padding: 16px<br>height: 72px / 56px<br>icon-size: 24x24px | ![User-Nav (LG)](assets/measurements/LG/extended/user-nav@1x.png) ![User-Nav (MD)](assets/measurements/MD/extended/user-nav@1x.png) |
| Main-navigation | padding: 8px<br>height: 48px / 40px<br>indicator: 1px | ![Main-nav (LG)](assets/measurements/LG/extended/main-nav@1x.png)![Main-nav (MD)](assets/measurements/MD/extended/main-nav@1x.png) |
| Sub-navigation | padding: 8px<br>height: 32px / 24px<br>indicator: 1px | ![Sub-nav (LG)](assets/measurements/LG/extended/sub-nav@1x.png) ![Sub-nav (MD)](assets/measurements/MD/extended/sub-nav@1x.png)|
| Flyout option | padding: 8px<br>height: 32px / 24px<br>margin-bottom: 4px<br>indicator: 1px | ![Flyout-option (LG)](assets/measurements/LG/extended/flyout-option@1x.png) ![Flyout-option (MD)](assets/measurements/MD/extended/flyout-option@1x.png)|

##### Collapsed

| Types | Attributes (LG / MD) | Preview |
|---|---|---|
| Height | complete: 106px / 74px<br>main-, sub- & user-navigation: 72px / 56px| ![Height (LG)](assets/measurements/LG/collapsed/height@1x.png)<br>![Height (MD)](assets/measurements/MD/collapsed/height@1x.png) |
| Width | complete: 1280px / 960px | ![Width (LG)](assets/measurements/LG/collapsed/width@1x.png)<br>![Width (MD)](assets/measurements/MD/collapsed/width@1x.png) |
| Logo | size: 80x98px / 56x68px<br>extension: 8px / 6px | ![Logo (LG)](assets/measurements/LG/collapsed/logo@1x.png)![Logo (MD)](assets/measurements/MD/collapsed/logo@1x.png) |
| Main-navigation | padding: 8px<br>height: 72px / 56px<br>indicator: 1px | ![Main-nav (LG)](assets/measurements/LG/collapsed/main-nav@1x.png)![Main-nav (MD)](assets/measurements/MD/collapsed/main-nav@1x.png) |
| Sub-navigation | padding: 8px<br>height: 72px / 56px<br>indicator: 1px | ![Sub-nav (LG)](assets/measurements/LG/collapsed/sub-nav@1x.png) ![Sub-nav (MD)](assets/measurements/MD/collapsed/sub-nav@1x.png)|
| User-navigation | padding: 16px<br>height: 72px / 56px<br>icon-size: 24x24px | ![User-nav (LG)](assets/measurements/LG/collapsed/user-nav@1x.png) ![User-nav (MD)](assets/measurements/MD/collapsed/user-nav@1x.png) |


### Tablet portrait & smartphone (SM & XS)

#### Spacing

- All the spacing for these breakpoints are identical.

| Types | Attributes (SM / XS) | Preview |
|---|---|---|
| Content | padding: 8px | ![Content (SM+XS)](assets/spacing/SM+XS/content@1x.png) |
| Dropdown | padding-top/-bottom: 16px<br>margin: 8px | ![Dropdown (SM+XS)](assets/spacing/SM+XS/dropdown@1x.png)
| User-navigation | padding: 16px (8+8) | ![User-Nav (SM+XS)](assets/spacing/SM+XS/user-navigation@1x.png) |
| Brand-navigation | offset: 8px<br>padding: 16px (8+8) | ![Brand-Nav (SM+XS)](assets/spacing/SM+XS/brand-navigation@1x.png) |
| Language | offset: 8px<br>padding: 16px (8+8) | ![Language (SM+XS)](assets/spacing/SM+XS/language@1x.png)

#### Measurements

| Types | Attributes (SM / XS) | Preview |
|---|---|---|
| Height | complete: 64px<br>user-navigation: 48px<br>search-field: 72px<br>main-& sub-navigation: depends on content<br>brand-navigation: depends on content<br>language: depends on content | ![Height (SM+XS)](assets/measurements/SM+XS/height@1x.png) |
| Width | width: 600px / 320px<br>flyout: 320px / 256px | ![Width (SM)](assets/measurements/SM/width@1x.png)![Width (XS)](assets/measurements/XS/width@1x.png) |
| Logo | size: 48x59px<br>extension: 5px  | ![Logo (SM+XS)](assets/measurements/SM+XS/logo@1x.png) |
| User-navigation | padding: 8px<br>height: 48px<br>icon-size: 24x24px | ![User-nav (SM+XS)](assets/measurements/SM+XS/user-nav@1x.png) |
| Burger-menu | padding: 8px<br>margin-bottom: 0px<br>height: 48px<br>icon-size: 24x24px | ![Burger-menu (SM+XS)](assets/measurements/SM+XS/burger-menu@1x.png)|
| Main-navigation | width: depends on content<br>padding-left: 16px<br>height: 40px<br>indicator: 1px | ![Main-nav (SM+XS)](assets/measurements/SM+XS/main-nav@1x.png) |
| Sub-navigation | width: depends on content<br>padding: 32px<br>height: 32px<br>indicator: 1px | ![Sub-nav (SM+XS)](assets/measurements/SM+XS/sub-nav@1x.png) |
| Brand-navigation | padding: 8px<br>height: 32px<br>margin-bottom: 2px<br>indicator: 1px |![Brand-nav (SM+XS)](assets/measurements/SM+XS/brand-nav@1x.png)|
| Language | padding: 8px<br>height: 32px<br>margin-bottom: 2px<br>indicator: 1px | ![Language (SM+XS)](assets/measurements/SM+XS/language@1x.png) |

---

## Position

| Types | Attributes | Preview |
|---|---|---|
| Addon | padding-right: 4px (LG)<br>padding-right: 8px (MD)<br>padding-right: 0px (SM+XS) | ![Addon (LG)](assets/position/LG/addon@1x.png)![Addon (MD)](assets/position/MD/addon@1x.png)![Addon (SM-XS)](assets/position/SM+XS/addon@1x.png) |

---

## Behavior

### On-scroll

- The header resizes in desktop and tablet (landscape) with an on-scroll effect - as given in our examples on the top of this description.
- There are two different behavior for the resizing depending on the navigation items shown.

### Main- & sub-navigation

- If **the first scroll-down** interaction is triggered, the whole header gets in its **collapsed** mode.
- If **the first scroll-up** interaction is triggered, the whole header gets in its **extended** mode.
- The animation of all elements starts with a global transition.
- If a sub-navigation exists all main-navigation items are hidden.
- Each menu item is clickable and the corresponding menu default page is loaded.
- If a menu item does not have a separate default page, the content of the first sub-nav page is displayed.

| Types | Preview |
|---|---|
| Main-navigation | ![Main-Nav (LG & MD)](assets/behavior/main-nav.gif) |
| Sub-navigation | ![Sub-Nav (LG & MD)](assets/behavior/sub-nav.gif) |

#### Recommendations

- We checked some settings for the transition that are given in the table below.

| Settings | Duration | Delay | CSS attribute | Bezier |
|---|---|---|---|---|
| Scroll down (Collapsed)| 0.6s | 0.15s | presets ease in & out | 0.64, 0.04, 0.35, 1 |
| Scroll up (Extended)| 0.4s | 0s | custom presets | 0.59, 0.06, 0.4, 0.95 |

### Overflow menu "More"

- The last main- or sub-navigation item is displayed as an overflow menu named "more..." if too many items should be presented than the possibility to show them.
- The keyword "more..." is only a recommended example and can be retitled to any appropriate term (i.e. "others…").
- The more menu is treated like a main-nav item. The items inside the overflow menu behave like sub-nav items.

### Flyout

- The main-navigation shows a flyout with all subitems **on hover** to grant a direct access for the user.
- Ends 40px from browser bottom edge or 8px from sticky bar.
- Maximal width is 33% of viewport width.
- Text breaks into multiple lines when maximal width is overreached.
- The alignment of the flyout depends on the positioned main-menu item.
- Therefore, the alignment can be left or right on the indicator.
- On mobile devices, the flyout is triggered on hold-tap and is visible until a sub-navigation is selected.
- The flyout **on focus** state is triggered by pressing Enter. To navigate through the elements, use the tab key or the up/down arrow on the keyboard.
- A flyout element is to be used exclusively in the main-nav.

| Types | Preview |
|--|---|
| Left | ![Flyout: left-alignment](assets/flyout/left-alignment@1x.png) |
| Right | ![Flyout: right-alignment](assets/flyout/right-alignment@1x.png) |


## Examples

- Clicking on the magnifier icon opens an active input-field that overlays the whole upper section (brand-, user-navigation and language selection) of the header.
- In collapsed mode, the main-navigation fades out completely and only the search field is shown.

![Examples (LG & MD)](assets/behavior/search.gif)

---

## What can be modified?

- Override the text and icons.
- Adjust the width of single symbols according to the text.
- Adjust the height if you delete navigation sections (i.e. main- or sub-navigation).
- Modify headers for your project needs by deleting single symbols or special sections (i.e. language or user-navigation section).

### Our workflow in Sketch

- To individualize the header in your product you need to detach/unlink the complete symbol from the SCHWARZ CAKE UI Web kit.
- Fill it with realistic content and scale every single symbol to the right width or height.
