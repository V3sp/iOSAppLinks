# iOSAppLinks

## Description

This repository serves as a comprehensive list of URL schemes for various iOS applications. URL schemes are a powerful feature that allows apps to be launched and controlled via specific URLs. This can be incredibly useful for deep linking, automation, and inter-app communication. The goal of this project is to gather and document these schemes in one place, making them easily accessible to developers and users alike.

## Why ?

Because, when I was looking for informations, how to run APP on iOS from Home-Assistant dashboard, I  wasn't able to find updated list ᓚᘏᗢ

## Known URL Schemes

Here you will find a list of known URL schemes for popular iOS applications. This list is continuously updated as new schemes are discovered and added.

### Native iOS Apps

- **Phone:** `tel://`
- **Messages:** `sms://`
- **Safari:** `http://` or `https://`
- **Contacts:** `contacts://`
- **Notes:** `mobilenotes://`
- **Reminders:** `x-apple-reminder://`
- **Clock:** `clock-alarm://`
- **Weather:** `weather://`
- **Stocks:** `stocks://`
- **Photos:** `photos-redirect://`
- **Camera:** `camera://`
- **Settings:** `App-prefs://`
- **App Store:** `itms-apps://`
- **iBooks:** `ibooks://`
- **Podcasts:** `pcast://`
- **Health:** `x-apple-health://`
- **Wallet:** `shoebox://`
- **Files:** `shareddocuments://`
- **Music:** `music://`
- **Maps:** `maps://`
- **FaceTime:** `facetime://`
- **Mail:** `mailto:`
- **Calendar:** `calshow://`
- **Find My:** `fmip1://`
- **Shortcuts:** `shortcuts://`
 
### Google Apps

- **Google Maps:** `comgooglemaps://`
- **Google Chrome:** `googlechrome://`
- **Google Gmail:** `googlegmail://`
- **YouTube:** `youtube://`
- **YouTube without question to start app:** `http://youtube.com/`
- 
### Communication Apps

- **WhatsApp:** `whatsapp://`
- **Signal:** `sgnl://`
- **Messenger:** `fb-messenger://`
- **Skype:** `skype://`
- **Telegram:** `tg://`
- **Viber:** `viber://`

### Other Apps

- **Spotify:** `spotify://`
- **Spotify whitout question to start app:** `https://open.spotify.com/`
- **Twitter/X:** `twitter://`
- **Facebook:** `fb://`
- **Instagram:** `instagram://`
- **LinkedIn:** `linkedin://`
- **Pinterest:** `pinterest://`
- **Snapchat:** `snapchat://`
- **TikTok:** `snssdk1128://`
- **Reddit:** `reddit://`
- **Slack:** `slack://`
- **Yelp:** `yelp://`
- **Zoom:** `zoomus://`
- **Venmo:** `venmo://`
- **Evernote:** `evernote://`
- **Dropbox:** `dbapi-1://`
- **Quora:** `quora://`
- **PayPal:** `paypal://`
- **Uber:** `uber://`
- **Lyft:** `lyft://`

Many apps support additional parameter, like Phone, mail, Google Maps

- **Google Maps - Point**: `comgooglemaps://?center=52.3976946,16.8581983&zoom=15`
- **Phone**: `tel://PHONENR`
- **Mail - with atributes**: `mailto://foo@example.com?subject=example&body=example`

## How to Create Your Own URL Scheme

If app do not have URL Schema, you can create own local scheme usign iOS App Shortcuts.

Creating your own URL scheme for an iOS app involves a few steps:

1 . Open app Shortcuts
2 . Create new shortcut with option **Open App** only
3 . Find the App you want to run
4 . Set Name for the Shortcut
5 . Save

Now you can use it as the following URL Schema: `shortcuts://run-shortcut?name=SHORTCUTNAME`

## Contributions

We welcome contributions! If you know of any URL schemes that are not listed here, feel free to add them. Please follow the contribution guidelines in the [CONTRIBUTING.md](CONTRIBUTING.md) file. Whether it's correcting an existing scheme or adding a new one, your help is appreciated in making this repository a valuable resource for the community.
