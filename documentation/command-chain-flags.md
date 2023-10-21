# Command Chain Flags

## Setup Guide

You can set up Command Chain Flags for specific features by following the steps below.

1. [Create a Command Chain](https://help.vivaldi.com/desktop/shortcuts/command-chains/#Create_a_Command_Chain) in the Quick Commands settings of Vivaldi Browser.
2. Give this command chain a name that matches the flag you would like to apply, for example `ac-disable-tabbar-full-width`.
3. [Open the Toolbar Editor](https://help.vivaldi.com/desktop/appearance-customization/edit-toolbars/#Customize_toolbars) and select "Command Chains" from the dropdown. Grab your created Command Chain and drag it into one of your toolbars.

## Precedence Rules

It is currently possible to have flags set that enable and disable the same feature at the same time. Additionally, each feature has a default state according to what I think is the best default experience for Antonio Lucio.

For each flag, the following precedence rules apply:

1. The `disable` flag always disables a feature.
2. The `enable` flag enables a feature if the `disable` flag is not set.
3. The default state of a feature applies if neither flag is set.

## Available Flags

### Grow width of tabs to occupy free space

*Enabled by default.*

To disable: `ac-disable-tabbar-full-width`

Individual tabs grow in width to occupy free space in their tab row.

### *(Coming soon!)* Show only domain name of URLs in address field

*Enabled by default.*

To disable: `ac-disable-addressfield-show-only-domain-name`

The address field only shows the domain name of an URL when it is not in focus.
