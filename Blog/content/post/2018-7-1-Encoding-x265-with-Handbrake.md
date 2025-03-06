---
title: "10/12-bit x265 encoding with Handbrake"
date: 2018-07-01
categories:
- Tutorials
keywords:
- Handbrake
- Tutorials
autoThumbnailImage: true
thumbnailImagePosition: "left"
coverImage: //i.imgur.com/d9Z9BPQ.png
metaAlignment: center
---
You may have seen x265 releases in the net and be suprised with the quality and size of those movies/tv-shows compared to the old x264. You might be wondering - How do i encode all those Blu-rays i got into x265 for storage?

That's when Handbrake comes in handy! You can easily encode any movies into x265 or even other formats (i.e mp4, mkv, mov and etc).
<!--more-->

As of today, the latest version of Handbrake (v1.1.1) has finally included x265 encode presets and also included support for 10/ 12-bits. Therefore, you can just select those presets and "BOOM!". You are set to go. For more details on x265 and 10/ 12-bit, read on.

---

## Why x265, and not x264?
* Smaller size, while preserving quality (i.e 4K, UHD videos)

##### The Downsides

x264 (H.264) can be seen in almost all releases and there are ton of devices that can encode/decode x264 files very fast and efficiently. x265 (H.265) is relatively a new technology and not many devices support it. Additionally, you will need much more computing power to decode x265 files because most of the processing are done by CPU and not video hardware (Bye! Raspberry Pi).

Thanks to Matt Gadient! He made an [Encoder Comparison](https://mattgadient.com/x264-vs-x265-vs-vp8-vs-vp9-examples/) between x264, x265, VP8 and VP9. Be sure to check it out!

---

## When to use 10-bit or 12-bit or not?
* Smaller size with 10-bit

The same problem comes when using 10 or 12-bits videos, there are not many devices that play those videos. Even if those devices "try" to play those videos, it will end up being very super-saturated. Furthermore, it takes so much RAM to encode those videos.

Matt Gadient also made [BITs comparison page](https://mattgadient.com/results-encoding-8-bit-video-at-81012-bit-in-handbrake-x264x265/) between 8, 10 and 12 bit encodes

---

## Requirements
* [Handbrake](https://handbrake.fr/)
* Good PC

Compared to x264, encoding x265 files requires a lot of processing power to encode which will provide you with a smaller file with amazing quality. High-end CPU and RAM are recommended to decrease time taken to encode each videos. Your PC's fans will blast like a wind turbine, so prepare to make sure the room is properly cooled.

--- 

## Settings

Follow the settings in the picture and you click "Start Encode" when you are done!

#### Summary tab:
![Step 1](https://i.imgur.com/BoWEI3n.png "Default tab")

#### Video tab:
![Step 2](https://i.imgur.com/l50sAfJ.png "Video tab")

---

# Whew!

Overall, the only benefit with x265 is smaller size. With the price of storage devices getting lower, i would recommend you guys to just stick with x264 when trying to encode and stick with x265 releases as to save internet bandwidth.