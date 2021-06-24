# Migration guide

## Update version 1.x to 2.x

### New Pricebox updates

![PriceBox update](assets/pricebox-update/pricebox-update.png)

- The harmonization steps for our pricebox are now fully implemented in our library. Everything is ready to be used! To be sure that the sizes fit to the new spacing & measurements there are small steps that need to be done. We would like to offer our guidance for you:
  - Select your placed symbol, right click and "Set to Original Size"
  - If you have placed a single pricebox item, keep in mind to check the spacings between the items. Our updated documentation will help you out!
  - If you detached the pricebox symbol, please check if the connected text-styles e.g. the basic quantitiy text and the label now have their own text-style.

### New symbol setup

- All symbols in our CAKE products now use the following predefined settings:
  - **layer-styles** for correct styling or to indicate a possible state of a symbol.
  - **text-styles** with the correct alignment (center, left, right).

Don't worry! Replacing symbols in layer-styles is not as complicated as it seems. New layer-styles have been implemented in our LIDL CAKE UI Fundamental library to optimize the workflow with the LIDL CAKE UI App library. Just try it!

- Update your LIDL CAKE UI libraries in Sketch:
  - Be sure to **compare** the changes in the overview carefully
  - Check your **layout and link your components** or texts with the new text & layer styles

### Replace color symbols

- As a result of the removal of the color icons from the pur LIDL CAKE UI Fundamental library, you should replace these icons in your components with our new layer styles.
- Here is a short workaround on how you can do this most easily and efficiently.

| Steps | Description | Preview |
|---|---|---|
| 1 | Display all used color symbols in your Sketch file by clicking on "Layer/Imported Symbols…" | ![Step 1: Imported symbol](assets/replace-color-symbol/1-imported-symbols.png) |
| 2| Select all displayed color symbols and unlink them from the original library file.<br>_Hint: The symbols now appear on your "Symbols" page_ | ![Step 2: Unlink symbol](assets/replace-color-symbol/2-unlink-symbols.png)|
| 3 | Select the artboard of **one** of the unlinked color symbols and run the plugin "[Symbol Instance Locator](https://github.com/sonburn/symbol-instance-locator?target=_blank)" | ![Step 3: Run plugin](assets/replace-color-symbol/3-run-plugin.png) |
| 4 | Jump directly to the located color symbol in a component by clicking on one of the shown instances | ![Step 4: Jump](assets/replace-color-symbol/4-jump.png) |
| 5 | Select the layer, detach it and update the occured shape with the desired layer-style. **Repeat this step** until there is no color symbol left in your document.<br>_Hint: Run the plugin on the artboards again to be 100% sure_ | ![Step 5: Detach symbol](assets/replace-color-symbol/5-detach-symbol.png) |
| 6 | Delete the artboard of the replaced color symbol<br>_Hint: If you receive this notification from Sketch you didn't replace all color symbols with a layer-style_ | ![Step 6: Sketch notification](assets/replace-color-symbol/6-sketch-notification.png)|

## Update version 6.x to 7.x (Fundamentals)

- We would like to keep our libraries and documentation up to date.
According to the official brand decision, the pricebox info is outdated. As a result, we are saying goodbye to this component in our Web, App and Mail libraries.

![Bye PriceBox info](assets/bye-pricebox-info.png)


## Update version 4.x to 5.x (Fundamentals)

### New Git repositories

- All CAKE library files are now at home in the Git repositories of Azure DevOps.
- Visit [setup](../../Getting\ started/Setup/Setup.md) and find a step-by-step tutorial how to get all future CAKE updates again.


### Global file renaming

- The name of **LIDL CAKE UI Core** has been changed to **LIDL CAKE UI Fundamental** due to the new library setup of some Lidl Digital's CI elements.
- The new LIDL CAKE UI Fundamental library only consists of symbols, text- and layer-styles that are *fundamental* to each of our products.

### Symbol transfer

- Some symbols have been moved from our LIDL CAKE UI Fundamental library (earlier CORE) to their explicit product library files (e.g. LIDL CAKE UI Web, App,…).
- Verify that all the following symbols are linked to the correct Sketch library:
  - Buttons
  - Forms
  - Tables

### Replace library

- Due to the symbol transfer you need to replace the symbols: buttons, forms and tables in every of your Sketch files with the help of the plugin **Automate**.

| Steps | Description | Preview |
|---|---|---|
| 1 |  After downloading the plugin click on "Plugins/Automate/Library" | ![Step 1: Automate](assets/1-automate.png)|
| 2 |  Choose "Replace library" from the given options | ![Step 2: Replace library](assets/2-replace-library.png)|
| 3 | Switch the settings under "Libraries of Imported Objects" to the new symbol location (e.g. LIDL-CAKE-UI_Web) and confirm your changes with "OK" | ![Step 3: New library](assets/3-new-library.png)|


### Symbol replacement

- The simple cookie alert no longer exists in our LIDL CAKE UI Web library.
- Please verify that you don't use the simple cookie alert anymore!
- Therefore replace the simple version with our current cookie alert.
