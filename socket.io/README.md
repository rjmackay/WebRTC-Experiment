![WebRTC Experiment!](https://muazkh.appspot.com/images/WebRTC.png)

--

[This webrtc experiment](https://webrtc-experiment.appspot.com/socket.io/) is using socket.io as signaling gateway.

## Just copy HTML and enjoy one-to-one video chat in your own site!

```html
<div id=pubnub ssl=on></div>
<script src="https://bit.ly/socket-io"></script>

<input type="text" id="room-name" placeholder="Room Name">
<button id="start-conferencing" style="display: inline;">Start One-to-One video chat!</button>

<div id="rooms-list"></div>
<div id="participants"></div>

<script src="https://bit.ly/RTCPeerConnection-v1-3"></script>
<script src="https://webrtc-experiment.appspot.com/RTCPeerConnection-Helpers.js"></script>

<!-- <optional> -->
<script>
    var iceServers = null;
    var socket_config = {
        publish_key: 'demo',
        subscribe_key: 'demo',
        ssl: true
    };
</script>
<!-- </optional> -->

<script src="https://webrtc-experiment.appspot.com/websocket/rtclib.js"> </script>
<script src="https://webrtc-experiment.appspot.com/websocket/ui.js"></script>
```

##Credits

* [Muaz Khan](http://github.com/muaz-khan)!

## License
Copyright (c) 2013 [Muaz Khan](https://plus.google.com/100325991024054712503) - Licensed under the MIT license.