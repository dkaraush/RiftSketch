# RiftSketch
![RiftSketch screenshot](http://i.imgur.com/3XwM1Rk.png)

https://www.youtube.com/watch?v=db-7J5OaSag

RiftSketch is a web-based live coding environment for Virtual Reality.

It lets you code a "sketch" in JavaScript, using
[ThreeJS](http://threejs.org/), while the world around you changes immediately
as you code.

It's quite a niche application since you need to have a VR HMD, be a
JavaScript programmer *and* be sufficiently familiar with Three.js but if you
meet that criteria it's surprisingly fun and engaging!

## Features
- Live-coding with real-time scene updates
- Collaborative coding. Share your creations.
- Convenient keyboard shortcuts
- Leap motion support
- Webcam pass-through

## Setup
If you happen to have a VR headset and you want to try it out yourself, download a
developer build of Firefox or Chrome that includes the WebVR APIs from
[MozVR](https://mozvr.com/#start) or
[Chrome WebVR](https://webvr.info/)
and visit http://brian.peiris.io/RiftSketch/

RiftSketch should also work on mobile phones, with Google Cardboard. Currently,
Firefox Nightly for Android and Chrome Dev for Android work the best. Bug reports
are welcome!

## Development
```
$ npm ci
$ npm run start
```
