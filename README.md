# AInspector Sidebar Test Releases

## Latest XPI file: `ai-sidebar-1.1.2-beta.1.xpi`

## Note: Firefox ESR version 52.7.3 is now required for testing unsigned add-ons

* Beginning with Firefox 48, released Aug. 2, 2016, users no longer have the option of installing unsigned add-ons using the method outlined below.
* Only the [Firefox Extended Support Release 52](https://www.mozilla.org/en-US/firefox/organizations/) provides this capability.

## Configuring Firefox Developer Edition

### Allow installation of unsigned add-ons

* In the Firefox location bar, type `about:config` and press Enter.
* Unless it has been disabled, a warning will be displayed and you will need to click the confirmation button that says “I'll be careful, I promise!”.
* In the about:config tab's “Search” field (top left), type `xpinstall`.
* In the list of filtered results, select `xpinstall.signatures.required`, right-click the item, and in the context menu, select “Toggle”.
* The result in the “Value” column should display `false`.

### Installing the XPI file: `ai-sidebar-1.1.2-beta.1.xpi`

* Save the downloaded XPI file in a familiar location on your computer's file system.
* In the Firefox main menu, select “Tools > Add-ons”. A tab entitled “Add-ons Manager” will appear.
* Select the menu button with the gear icon at the top, and from its menu, select “Install Add-on From File...”.
* Choose the downloaded XPI file, and confirm that you want to install it.
* Select “Restart”.
