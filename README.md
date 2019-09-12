# WP Inventory - Logging Add-On
by [WP Inventory](https://www.wpinventory.com)
An add-on for the WordPress plugin WP Inventory.

This add-on enables logging various data to a persistent log to assist in troubleshooting elusive issues.

### Warning: 
It is recommend that you only install this plugin if recommended / requested by the WP Inventory support team.

### Installation
Install this plugin in your WordPress install.  There are many resources on the internet that give excellent
instructions on how to do this (just Google "install wordpress plugin")

Activate the plugin.

### Usage
1. In the WP admin dashboard, go to "WP Inventory", and choose the "Settings" submenu item.
2. Go to the "General" tab, then the "Logging Settings" subtab.
3. In the WP admin dashboard, go to "WP Inventory", and choose the "Logging" submenu item.
4. Under "Enable Logging", set to "Yes".
5. **Warning**: Under "log to screen" - setting this to "Yes" may cause unexpected problems, so avoid usage, 
and if you do use it, use this with extreme care.

### How it Works
This plugin "watches" all WordPress actions and hooks that pertain to the WP Inventory plugin and add-ons.  It does
this by inspecting and monitoring all hooks (actions and filters) that begin with `wpim_` or `wpinventory_`.

Where possible, this tool captures the data state both before and after the hook has run.

This output is written to a text file, which can be viewed in the tool's dashboard,
or downloaded and sent to support.
