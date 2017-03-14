# AInspector Sidebar Test Releases

## Latest XPI file: `ai-sidebar-1.1.0.xpi`

## Note: Firefox Developer Edition is now required for testing unsigned add-ons

* As of 2 Aug 2016, the Firefox 48 release version no longer provides the option of installing unsigned add-ons using the method outlined below.
* Only the [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) provides this capability.
* By default, Firefox Developer Edition will use a separate profile, with separate configuration settings, from any other Firefox version you have installed.

## Configuring Firefox Developer Edition

### Turn off multi-process mode

* In the Firefox “hamburger” menu, select “Options” on Windows, or “Preferences” on Mac.
* On the “General” tab, in the “Startup” section, **uncheck**  “Enable multi-process Firefox Developer Edition”.
* Restart Firefox.

### Allow installation of unsigned add-ons

* In the Firefox location bar, type `about:config` and press Enter.
* Unless it has been disabled, a warning will be displayed and you will need to click the confirmation button that says “I'll be careful, I promise!”.
* In the about:config tab's “Search” field (top left), type `xpinstall`.
* In the list of filtered results, select `xpinstall.signatures.required`, right-click the item, and in the context menu, select “Toggle”.
* The result in the “Value” column should display `false`.

### Installing the XPI file: `ai-sidebar-1.1.0.xpi`

* Save the downloaded XPI file in a familiar location on your computer's file system.
* In the Firefox main menu, select “Tools > Add-ons”. A tab entitled “Add-ons Manager” will appear.
* Select the menu button with the gear icon at the top, and from its menu, select “Install Add-on From File...”.
* Choose the downloaded XPI file, and confirm that you want to install it.
* Select “Restart”.
