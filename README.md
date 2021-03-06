# SMS Drive

[![PyPI status](https://img.shields.io/pypi/status/ansicolortags.svg)](https://play.google.com/store/apps/details?id=devesh.ephrine.backup.sms)
[![Generic badge](https://img.shields.io/badge/Beta_Version-0.0.1-yellow.svg)](https://play.google.com/store/apps/details?id=devesh.ephrine.backup.sms) [![Generic badge](https://img.shields.io/badge/Download-APK-green.svg)](https://install.appcenter.ms/orgs/ephrine-apps/apps/sms-drive/distribution_groups/sms%20drive)  [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/ephrine/SMS-Drive/blob/master/LICENSE) [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/deveshrx) [![GitHub stars](https://img.shields.io/github/stars/Naereen/StrapDown.js.svg?style=social&label=Star&maxAge=2592000)](https://github.com/ephrine/SMS-Drive/stargazers/) [![GitHub contributors](https://img.shields.io/github/contributors/Naereen/StrapDown.js.svg)](https://github.com/ephrine/SMS-Drive/graphs/contributors/)
![Android Build APK](https://github.com/ephrine/SMS-Drive/workflows/Android%20Build%20APK/badge.svg)

Back-up &amp; Sync Messages on your Device

### How to Build & Compile Debug APK:
Step 1: Create a [Firebase Project](https://console.firebase.google.com/) and add SMS Drive App in it with package name <code>devesh.ephrine.backup.sms.debug</code>

Step 2: Download <code>google-services.json</code> file from console and add it into project location <code>/app/google-services.json</code>

Step 3: Create a file  <code>smsdrive.local.properties</code> in parent directory(SMS-Drive) and Add following environmental variables into your <code>smsdrive.local.properties</code> file 


>sign.key.password=YOUR_PASSWORD <br>
>sign.key.alias=YOUR_ALIAS <br>
>sign.key.path=C:\\\YOUR_KEY_PATH <br>
>google.services.json=https:\\\www.YOUR-WEBSITE.com\KEY ##Optional <br>
>g.license.key=YOUR_GOOGLE_LICENSE_KEY_FROM_PLAY_STORE_CONSOLE ##optional<br>
>msappcenter=0000<br>
>gplaysubscriptionid1=0000<br>
>msappcenter=your_key <br>
>admobappid=your_key <br>
>admobbanner1=your_key <br>
>admobinitid=your_key <br>
>mopubadunitid=your_key <br>
>huaweiproductid=your_key <br>
>samsungiapitem=your_key <br>
>facebookappid=your_key <br>
>fbloginprotocolscheme=your_key <br>


Step 4: Build & Run


### Developers:
Devesh Chaudhari [@DeveshRx](https://GitHub.com/deveshrx)
