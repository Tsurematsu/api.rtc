# WebRTC API Project

## Description

A real-time communication API built with WebRTC technology for enabling peer-to-peer video, audio, and data streaming.

## Features

- Video/Audio streaming
- Data channels
- Signaling server
- Room management
- Peer connections

## Installation

```bash
npm install
```

## Configuration

```javascript
// Configure your STUN/TURN servers
const configuration = {
  iceServers: [
    { urls: 'stun:stun.server.com:3478' },
    { urls: 'turn:turn.server.com:3478' }
  ]
}
```

## Usage

```javascript
// Basic example
const rtcConnection = new RTCPeerConnection(configuration)
```

## API Endpoints

- `/connect` - Establish connection
- `/room` - Create/Join room
- `/signal` - Handle signaling

## Requirements

- Node.js v14+
- WebRTC compatible browser
- STUN/TURN server

## License

MIT

## Contributing

Pull requests are welcome. Please read CONTRIBUTING.md first.
