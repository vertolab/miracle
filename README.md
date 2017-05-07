### [List of commands](commands.md)

# Mira Cue: Kodi control over Alexa

This addon is intended to control Kodi using Amazon Alexa.

How is it different from other solutions?

You **only** need Kodi and Alexa. That's it.
**No need for** Heroku / AWS or any of that.

[![youtube video](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/youtube.png)](https://www.youtube.com/watch?v=dkAZSHDixFk)

## Installation

Only 5 installation steps:

1. [Allow Unknown sources](#allow-unknown-sources) (if you havn't already)
2. [Add Verto Lab source](#add-verto-lab-source) (http://kodi-repo.vertolab.com/)
3. [Add Verto Lab Repo](#add-verto-lab-repo)
4. [Install Mira Cue Add-on](#install-mira-cue-add-on)
5. [Pair Mira Cue Addon with Mira Cue Alexa Skill](#pair-mira-cue-kodi-addon-with-mira-cue-alexa-skill)

### Allow Unknown sources

1. Select **Add-ons**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/1.png)
2. Select the **Settings cogwheel**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/2.png)
3. If *Unknown sources* is switched off
    1. Select **Unknown sources**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/3.png)
    2. Select **Yes**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/4.png)
4. Return **back**, then **back** again to the main screen

### Add Verto Lab source

1. Select the **Settings cogwheel**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/5.png)
2. Select **File manager**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/6.png)
3. Select **Add source**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/7.png)
4. Select **&lt;None>**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/8.png)
5. Type **http://kodi-repo.vertolab.com/**, and select **OK**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/9.png)
6. Select the lower text box
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/10.png)
7. Type **Verto Lab**, and select **OK**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/12.png)
8. Select **OK**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/13.png)
9. Return **back**, then **back** again to the main screen

### Add Verto Lab Repo

1. Select **Add-ons**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/14.png)
2. Select the **Enter add-on browser**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/15.png)
3. Select **Install from zip file**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/16.png)
4. Select **Verto Lab**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/17.png)
5. Select **Repository**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/18.png)
6. Select **repository-vertolab-1.x.x**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/19.png)
7. Select **repository-vertolab-1.x.x.zip**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/20.png)
8. Wait few seconds for *Add-on installed* notification.
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/21.png)

### Install Mira Cue Add-on

1. Select **Install from repository**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/22.png)
2. Select **Verto Lab Repo**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/23.png)
3. Select **Program add-ons**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/24.png)
4. Select **Mira Cue**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/25.png)
5. Select **Install**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/26.png)
6. Wait few seconds for *Add-on installed* notification.

### Pair Mira Cue Kodi Addon with Mira Cue Alexa Skill

1. Select **Mira Cue**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/28.png)
2. Select **Run**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/29.png)
3. Ask your Alexa-enabled device to enable the Mira Cue skill: **"Alexa, enable Mira Cue skill"**
    1. If you're having problems with activating the skill via voice, go to your Alexa app and enable the skill through the app.
4. Once the Mira Cue Alexa Skill is enabled, Select **OK**.
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/30.png)
5. Ask your Alexa-enabled device to pair with your Kodi: **"Alexa, ask Mira Cue to pair with code XXXX XXXX"** (replace XXXX XXXX with the code that appears in the dialog).
    1. Your pairing code should contain 8 digits. See the marked frame in the following screenshot:
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/31.png)
6. Wait for Alexa notification of success.
7. Select **OK**
![image](https://raw.githubusercontent.com/vertolab/miracle/master/resources/guide_screenshots/32.png)
8. Say *"Alexa, ask Mira Cue to go home"* to return to the main screen

That's it :) Now you can...

### [Give it a try!](commands.md)

 - *"Alexa ask Mira Cue to set volume to 5"*
 - *"Alexa ask Mira Cue to shuffle all music"*
 - [And many more](commands.md)

## General Addon Comments

The addon uses an always-on, encrypted connection to a server which forwards requests from the paired Alexa. In addition, all communication is only one-way (incoming into Kodi) so no sensitive user data is leaving the device. 

To reduce stress on server resources, most processing is done in the addon itself. This allows the community to overview the implementation and suggest improvements.

### Developers
Feel free to fork this repository, make changes and suggest them as improvements via pull requests.

Credits to https://github.com/m0ngr31/kodi-alexa
Some code in this repository is based on kodi-alexa.
