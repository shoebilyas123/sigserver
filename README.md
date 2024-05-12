# SigServer
  Signalling server for two clients to exchange SDPs for webRTC peer to peer connection.

## Socket Events
### room:join:request
    ```js
      socket.on(JOIN_ROOM, ({ roomNumber, alias }) => {
        ...
      }
    ```
    roomNumber: The socket room id that the client provides from the back-end.
    alias: The username or email that will be mapped to the socketID and also used by the client in the front-end to identify unique users.

## Disclaimer
  The project is still in an early development and the code structure somewhat coupled to my personal video call app. Nevertheless, it can be used externally.
