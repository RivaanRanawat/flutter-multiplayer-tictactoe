# Multiplayer TicTacToe Game

A completely Responsive Multiplayer TicTacToe Game- Works on Android, iOS, Web & Desktop! 

## Features
- Create/Join Room
- Play Realtime
- Display Points
- Round & Game Winner
- Responsive Glow Themed UI
- Cross Platform Game

## YouTube
I have created a tutorial based on this, do check it out on my channel [Rivaan Ranawat](https://youtu.be/Aut-wfXacXg)

<p align="center">
  <img width="600" src="https://github.com/RivaanRanawat/flutter-multiplayer-tictactoe/blob/master/screenshot.png" alt="Youtube Tutorial Image">
</p>


## Installation
After cloning this repository, migrate to ```flutter-multiplayer-tictactoe``` folder.

Install dependencies (Client Side)
```bash
flutter pub get
```

Install dependencies (Server Side)

```bash
cd server && npm install
```

Start the server

```bash
npm run dev
```

Configure for MacOS:
Head to macos/Runner and make sure the following keys are present in DebugProfile.entitlements and Release.entitlements
```bash
<key>com.apple.security.network.server</key>
<true/>
<key>com.apple.security.network.client</key>
<true/>
```

Run App
```bash
flutter run // After selecting the device you want to test on
```

## Tech Used
**Server**: Node.js, Express, Socket.io, Mongoose, MongoDB

**Client**: Flutter, Provider
    
## Feedback

If you have any feedback, please reach out to me at namanrivaan@gmail.com or on Instagram at optimalcoding.

