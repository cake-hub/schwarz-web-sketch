# Migration guide

## Update version 4.x to 5.x

### New symbol setup

- All symbols in our CAKE products now use the following predefined settings:
  - **layer-styles** for correct styling or to indicate a possible state of a symbol.
  - **text-styles** with the correct alignment (center, left, right).

Don't worry! Replacing symbols in layer-styles is not as complicated as it seems. New layer-styles have been implemented in our SCHWARZ CAKE UI Fundamental library to optimize the workflow with the SCHWARZ CAKE UI Web library. Just try it!

- Update your SCHWARZ CAKE UI libraries in Sketch:
  - Be sure to **compare** the changes in the overview carefully
  - Check your **layout and link your components** or texts with the new text & layer styles

### Replace color symbols

- As a result of the removal of the color icons from the pur SCHWARZ CAKE UI Fundamental library, you should replace these icons in your components with our new layer styles.
- Here is a short workaround on how you can do this most easily and efficiently.

| Steps | Description | Preview |
|---|---|---|
| 1 | Display all used color symbols in your Sketch file by clicking on "Layer/Imported Symbols…" | ![Step 1: Imported symbol](assets/replace-color-symbol/1-imported-symbols.png) |
| 2| Select all displayed color symbols and unlink them from the original library file.<br>_Hint: The symbols now appear on your "Symbols" page_ | ![Step 2: Unlink symbol](assets/replace-color-symbol/2-unlink-symbols.png)|
| 3 | Select the artboard of **one** of the unlinked color symbols and run the plugin "[Symbol Instance Locator](https://github.com/sonburn/symbol-instance-locator?target=_blank)" | ![Step 3: Run plugin](assets/replace-color-symbol/3-run-plugin.png) |
| 4 | Jump directly to the located color symbol in a component by clicking on one of the shown instances | ![Step 4: Jump](assets/replace-color-symbol/4-jump.png) |
| 5 | Select the layer, detach it and update the occured shape with the desired layer-style. **Repeat this step** until there is no color symbol left in your document.<br>_Hint: Run the plugin on the artboards again to be 100% sure_ | ![Step 5: Detach symbol](assets/replace-color-symbol/5-detach-symbol.png) |
| 6 | Delete the artboard of the replaced color symbol<br>_Hint: If you receive this notification from Sketch you didn't replace all color symbols with a layer-style_ | ![Step 6: Sketch notification](assets/replace-color-symbol/6-sketch-notification.png)|


---


## Update version 3.x to 4.x


### New Git repositories

- All CAKE library files are now at home in the Git repositories of Azure DevOps.
- Visit [setup](../../Getting_started/Setup/Setup.md) and find a step-by-step tutorial how to get all future CAKE updates.


---


### Global file renaming

- The name of **SCHWARZ CAKE UI Core** has been changed to **SCHWARZ CAKE UI Fundamental** due to the new library setup of some SCHWARZ Digital's CI elements.
- The new SCHWARZ CAKE UI Fundamental library only consists of symbols, color variables, text- and layer-styles that are *fundamental* to each of our products.


---


### Symbol transfer

- Some symbols have been moved from our SCHWARZ CAKE UI Fundamental library (former CORE) to their explicit product library files (e.g. SCHWARZ CAKE UI Web,…).
- Verify that all the following symbols are linked to the correct Sketch library:
  - Buttons
  - Forms
  - Tables


---


### Replace library

- Due to the symbol transfer you need to replace the symbols: buttons, forms and tables in every of your Sketch files with the help of the plugin [Library Replacer](https://github.com/sketch-hq/library-replacer-sketchplugin/releases/tag/v1.0.3).


---


### Symbol replacement

Many changes have been made to our library files as a result of the new **SCHWARZ Design Manual**.

- Almost every symbol and component has been adjusted.
- The biggest changes have been made for colors, fonts, icons (Fundamental) and other components (Web).


---


### General information

- Regard the list below for a detailed overview what exactly changed.

#### Added

- New radius symbol


#### Changed

- Font-weight of the Helvetica New LT Pro:
  - Condensed to **Light Condensed**
  - Bold Condensed to **Medium Condensed**
- SCHWARZ color set and their naming to new brand colors (i.e. info gets brand-info, warning gets brand-attention,…)
- Icons to new icon set
- Logo to the new SCHWARZ enterprise logo


#### Removed

- All gradients
- 2/3 of the icon set


---


### Added symbols

#### Colors


##### brand-secondary

- base: #41053C


##### brand-info

- darkest: #2D3C50


##### brand-attention

- darkest: #AF6E00


##### danger

- darkest: #5A0006


##### success

- darkest: #02421E


##### gray

- dark: #505050

#### Icons

##### interaction

- arrows-expand
- calendar
- cogwheel
- controls
- file
- fingerprint
- sync
- upload

---


### Changed symbols

#### Colors


##### brand-primary

- base: #791F82 to #6E1E6E


##### info to brand-info

- base: #0050AA to #5F7DAA
- dark: #00438F to #4B6487
- darker: #003673 to #3C506E


##### warning to brand-attention

- base: #BE591D to #FFD746
- dark: #9F4B18 to #E6B43C
- darker: #813C14 to #C8912D


##### danger

- base: #E60A14 to #E3000F
- dark: #C10811 to #B5000C
- darker: #9C070E to #880009


##### success

- base: #348553 to #05A54B
- dark: #2C7046 to #04843C
- darker: #235A38 to #03632D


##### gray

- base: #4E5761 to #878787
- lightest: #F1F2F3 to #EBEBEB
- lighter: #E3E4E5 to #C6C6C6
- light: #C6C9CC to #9D9D9D


#### Shadow

- default: 0px 2px 4px 0px to default: 0px 1px 2px 0px


#### Icons

##### expression

- conversation-ballons
- exclamation-circle
- exclamation-triangle
- hook-circle
- information-circle
- questionmark-circle

##### interaction

- arrow-left-circle
- arrow-right-circle
- arrows-vertical
- bars-horizontal
- camera
- clock
- crosshair
- download
- eye-close
- eye-open
- hook
- magnifier
- magnifier-minus
- magnifier-plus
- map
- map-marker
- placeholder
- printer
- social-share

##### navigation

- arrow-down
- arrow-left
- arrow-right
- arrow-up
- cross
- undo

##### status

- bell-regular
- bell-solid
- bookmark-regular
- bookmark-solid
- heart-regular
- heart-solid
- star-regular
- star-solid


---


### Removed symbols

#### Colors

##### brand-primary

- background: #F9F6FA
- lighter: #E9DAEA
- light: #D3B6D6
- dark: #651A6D
- darker: #521558

##### info

- background: #F5F8FC
- light: #D6E3F1
- lighter: #ADC7E4

##### mark

- background: #FFFEF5
- light: #FFFAAD
- lighter: #FFFDD6
- dark: #FBCB03
- darker: #F7A606

##### danger

- background: #FEF5F6
- light: #F7B0B3
- lighter: #FBD8D9

##### success

- background: #F7FAF8
- light: #BED8C8
- lighter: #DEEBE3

##### warning

- background: #FCF8F6
- lighter: #F5E4DB
- light: #EACAB6

##### gray

- darker: #353B42


#### Shadow

- flyout: basic-black, 0px 3px 3px 0px, 0.15


#### Icons

##### animals

- removed all icons

##### expression

- award
- certificate
- comment
- hook-shield
- lightbulb-on
- newspaper
- paragraph-circle
- thumbs-up-ballon

##### interaction

- 360-degree
- book-open
- bulletlist
- checklist
- ellipsis-horizontal
- envelope-close
- envelope-open
- external-link
- hand-pointer
- flyer
- house
- lock-close
- pause-circle
- pencil
- phone
- phone-envelope
- play-circle
- shopping-cart-1
- store
- store-magnifier
- plus
- trash
- user


##### food & beverage

- removed all icons

##### nature

- removed all icons

##### payment

- removed all icons

##### smiley

- removed all icons

##### status

- thumbs-down-regular
- thumbs-down-solid
- thumbs-up-regular
- thumbs-up-solid

##### transport & logistic

- removed all icons
