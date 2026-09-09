<meta property="og:image"
    content="https://raw.githubusercontent.com/erkserkserks/h264ify/master/icons/icon128.png"/>

# no-av1-ify


![](https://raw.githubusercontent.com/erkserkserks/h264ify/master/noncode/yt_screenshot.png)

# About
The original extension h264ify is a Chrome/Firefox extension that makes YouTube stream H.264 videos instead of VP8/VP9 videos, but it's not really suitable for newer hardware.

By default, YouTube usually streams AV1 encoded video, which is not hardware-accelerated in some not-new gpus.

no-av1-ify only disallow av1 video decoding to reduce cpu usage. Try this if your gpu only doesn't support av1.

# Installation
1. Clone this repo.

2. Go to chrome://extensions, enable Developer Mode.

3. Click the Load unpacked button and select the cloned repo directory.

If all goes well, when you right click a video and select "Stats for nerds", you should see that the codec is vp09 instead of the default vp01.
