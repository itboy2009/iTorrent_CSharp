# iTorrent - iOS Torrent client App

![](https://www.bitrise.io/app/fb04a8ae5980d0e0/status.svg?token=XwFNndLUAUGMJC1FgOKMFw&branch=master)
![](https://img.shields.io/badge/iOS-9.3+-blue.svg)

## Screenshots

![pic](https://user-images.githubusercontent.com/9553519/39924916-59d76598-5532-11e8-83ee-f87877492603.png)

**Download .ipa:** ([Google Drive](https://drive.google.com/open?id=1lCdjScAPKwgkWRdWrgx6qdFX2vsoX5Gt))

## Info

This app was written in Visual Studio - Xamarin.iOS

It is an ordinary torrent client for iOS with Files app support.

What can this app do:
- Download in the background by using music or microphone hack
- Add torrent files from Share menu (Safari and other apps)
- Store files in Files app (only iOS 11)
- Support for <iOS 11 versions, like sending files directly from app
- Download torrent by link
- Download torrent by magnet (may not work)
- Send notification on torrent downloaded
- Select files to download
- Share files by FTP Server
- ??? 

## Libraries used

- [MonoTorrent (joshmackey fork)](https://github.com/joshmackey/monotorrent)
- [MooFTPServ](https://github.com/mooware/mooftpserv)

## Known bugs

- Microphone writing background mode might require several attempts to enable. Just try again by opening and closing the app until the status bar becomes red, so HIGHLY recommended to not use it.
- Magnet links may not work, try to turn on DHT in settings, but it could break normal downloads.

## Donate for donuts

- VISA CARD - 4890 4944 7168 8218
- [QIWI Moneybox](https://qiwi.me/c5ec30ff-21d6-428b-9a10-29a1d18242db)


## License

Copyright (c) 2018 XITRIX

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
