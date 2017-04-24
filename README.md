# Kodi and Alexa integration

This addon is intended to pair your Kodi with Alexa-enabled services such as Amazon Echo.

## Installation

### Install the Miracle Alexa Addon from the Kodi repositories

Start by following the Fusion repository installation instructions, as described in parts 1 through 3 of [their guide](https://www.tvaddons.ag/kodi-addons-dummies/) (no need to follow parts after part 3).

Then you should open the Indigo addon that was just installed, select "Addon Installer", navigate to "Program Addons", select "Next Page" at the bottom, then locate "Miracle" in the list. Install the Miracle addon and wait for the completion notification.

### Pair the Miracle Addon with the Miracle Skill
Highlight Add-ons in the menu, and click on the Miracle add-on

![alt text](https://github.com/vertolab/miracle/blob/master/resources/guide_screenshot_11.png "Miracle in the add-ons section")

Now tell your Alexa-enabled device to enable the Miracle skill. If you're having problems with activating the skill via voice, go to your Alexa app and enable the skill through the app. Click OK when done.

![alt text](https://github.com/vertolab/miracle/blob/master/resources/guide_screenshot_7.png "Skill installation dialog")

As the dialog instructs, ask the Miracle skill to pair with the code displayed in your dialog

![alt text](https://github.com/vertolab/miracle/blob/master/resources/guide_screenshot_8.png "Pair dialog")

When the skill tells you pairing was successful you can dismiss the dialog and click OK.

Congratulations, you can now control your Kodi without having to reach out to your remote, mouse or keyboard!

## General Addon Comments

The addon uses an always-on, encrypted connection to a server which forwards requests from the paired Alexa. In addition, all communication is only one-way (incoming into Kodi) so no sensitive user data is leaving the device. 

To reduce stress on server resources, most processing is done in the addon itself. This allows the community to overview the implementation and suggest improvements.

Feel free to fork this repository, make changes and suggest them as improvements via pull requests.
