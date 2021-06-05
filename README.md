# VR-Pixel-Streaming
An attempt to adapt the pixel streaming plugin with Mobile VR

## Current Plan
The main idea until now is to connect the pixel streaming functionality with a flutter app and test if it's possible for real time VR streaming.

- [x] Know how the Js Part works
- [x] Build a simple flutter demo with the `sensors` plugin
- [ ] Return the Accelerometer and Gyroscope data via webrtc
- [ ] See how can we connect the data with VR headset in ue4

## What have been learnt so far
1. The `cirrus.js` is the first file to run when the server starts
2. OpenXR will not be the solution to the problem, we need a runtime or a custom driver to communicate with steamVR or a solution from inside the engine.
3. This will take some time.

## Nothing can be done until the release of ue 4.27 with the deployment-ready PixelStreaming plugin (they made big differences on the project)
