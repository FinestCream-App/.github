# FinestCream
FinestCream is a no-code solution for creating Socket.IO and WebSocket mock servers. FinestCream simulates the behavior of a real server for testing client events.

- Socket.IO and WebSocket Mock Server
- Test Client Events
- Public and Private Teams
- Collaborate with Users
- Group Events in Collections

## Socket.IO Features
- Listen and Emit Events
- Acknowledgement
- Multiple Arguments
- Dynamic Variables
- JSON Reponses

## Socket.IO Connection
```typescript
import { io } from 'socket.io-client';

socket = io(
    'https://api.finestcream.com/<TEAM_ID>',
    { extraHeaders: { authorization: '<API_TOKEN>' }}
    // Extra headers are not needed for public teams
)
```

## WebSocket Features
- Listen and Send Events
- Dynamic Variables
- JSON Reponses

## WebSocket Connection
```typescript
socket = new WebSocket('wss://api.finestcream.com/<TEAM_ID>');
```
