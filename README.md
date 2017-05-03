# Miracle: Alexa control over Kodi

This addon is intended to pair your Kodi with Alexa-enabled services such as Amazon Echo.

## Installation

### Allow Unknown sources

1. Select **Add-ons**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/1.png)
2. Select the **Settings cogwheel**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/2.png)
3. If *Unknown sources* is switched off
    1. Select **Unknown sources**
    2. Select **Yes**
4. Return **back**, then **back** again to the main screen

### Add Verto Lab source

1. Select the **Settings cogwheel**
2. Select **File manager**
3. Select **Add source**
4. Select **<None>**
5. Type **http://kodi-repo.vertolab.com/**, and select **OK**
6. Select the lower text box
7. Type **Verto Lab**, and select **OK**
8. Select **OK**
9. Return **back**, then **back** again to the main screen

### Add Verto Lab Repo

1. Select **Add-ons**
2. Select the **Enter add-on browser**
3. Select **Install from zip file**
4. Select **Verto Lab**
5. Select **Repository**
6. Select **repository-vertolab-1.x.x**
7. Select **repository-vertolab-1.x.x.zip**
8. Wait few seconds for *Add-on installed* notification.

### Install Miracle Add-on

1. Select **Install from repository**
2. Select **Verto Lab Repo**
3. Select **Program add-ons**
4. Select **Miracle**
5. Select **Install**
6. Wait few seconds for *Add-on installed* notification.

### Pair Miracle Kodi Addon with Miracle Alexa Skill

1. Select **Miracle**
2. Select **Run**
3. Ask your Alexa-enabled device to enable the Miracle skill: **"Alexa, enable Miracle Kodi skill"**
    1. If you're having problems with activating the skill via voice, go to your Alexa app and enable the skill through the app.
4. Once the Miracle Alexa Skill is enabled, Select **OK**.
5. Ask your Alexa-enabled device to pair with your Kodi: **"Alexa, ask Miracle Kodi to pair with code XXXX XXXX"** (replace XXXX XXXX with the code that appears in the dialog).
6. Wait for Alexa notification of success.
7. Select **OK**
8. Return **back**, then **back** again to the main screen

Congratulations, you can now control your Kodi without having to reach out to your remote, mouse or keyboard!

## General Addon Comments

The addon uses an always-on, encrypted connection to a server which forwards requests from the paired Alexa. In addition, all communication is only one-way (incoming into Kodi) so no sensitive user data is leaving the device. 

To reduce stress on server resources, most processing is done in the addon itself. This allows the community to overview the implementation and suggest improvements.

### Developers
Feel free to fork this repository, make changes and suggest them as improvements via pull requests.

