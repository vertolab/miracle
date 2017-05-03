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
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/3.png)
    2. Select **Yes**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/4.png)
4. Return **back**, then **back** again to the main screen

### Add Verto Lab source

1. Select the **Settings cogwheel**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/5.png)
2. Select **File manager**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/6.png)
3. Select **Add source**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/7.png)
4. Select **&lt;None>**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/8.png)
5. Type **http://kodi-repo.vertolab.com/**, and select **OK**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/9.png)
6. Select the lower text box
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/10.png)
7. Type **Verto Lab**, and select **OK**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/12.png)
8. Select **OK**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/13.png)
9. Return **back**, then **back** again to the main screen

### Add Verto Lab Repo

1. Select **Add-ons**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/14.png)
2. Select the **Enter add-on browser**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/15.png)
3. Select **Install from zip file**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/16.png)
4. Select **Verto Lab**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/17.png)
5. Select **Repository**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/18.png)
6. Select **repository-vertolab-1.x.x**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/19.png)
7. Select **repository-vertolab-1.x.x.zip**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/20.png)
8. Wait few seconds for *Add-on installed* notification.
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/21.png)

### Install Miracle Add-on

1. Select **Install from repository**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/22.png)
2. Select **Verto Lab Repo**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/23.png)
3. Select **Program add-ons**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/24.png)
4. Select **Miracle**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/25.png)
5. Select **Install**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/26.png)
6. Wait few seconds for *Add-on installed* notification.

### Pair Miracle Kodi Addon with Miracle Alexa Skill

1. Select **Miracle**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/28.png)
2. Select **Run**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/29.png)
3. Ask your Alexa-enabled device to enable the Miracle skill: **"Alexa, enable Miracle Kodi skill"**
    1. If you're having problems with activating the skill via voice, go to your Alexa app and enable the skill through the app.
4. Once the Miracle Alexa Skill is enabled, Select **OK**.
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/30.png)
5. Ask your Alexa-enabled device to pair with your Kodi: **"Alexa, ask Miracle Kodi to pair with code XXXX XXXX"** (replace XXXX XXXX with the code that appears in the dialog).
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/31.png)
6. Wait for Alexa notification of success.
7. Select **OK**
![alt text](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/32.png)
8. Return **back**, then **back** again to the main screen

Congratulations, you can now control your Kodi without having to reach out to your remote, mouse or keyboard!

## General Addon Comments

The addon uses an always-on, encrypted connection to a server which forwards requests from the paired Alexa. In addition, all communication is only one-way (incoming into Kodi) so no sensitive user data is leaving the device. 

To reduce stress on server resources, most processing is done in the addon itself. This allows the community to overview the implementation and suggest improvements.

### Developers
Feel free to fork this repository, make changes and suggest them as improvements via pull requests.

Credits to https://github.com/m0ngr31/kodi-alexa
Some code in this repository is based on kodi-alexa.
