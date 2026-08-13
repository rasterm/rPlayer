# rPlayer

rPlayer is a video and image application built on the public rasterm C++ API. It owns all multimedia concerns:

- OpenCV image/video decoding and scaling
- FFmpeg audio demuxing, decoding, and resampling
- Miniaudio playback
- Audio master frame timing and late frame dropping
- Adaptive playback resolution
- CSV performance metrics

Download and move the rasterm.sln to the root of `rasterm` directory, and rPlayer source code to `apps/rPlayer` directory. You can build with vs2022 or cmake, the output will be at:

```text
apps/rPlayer/build/
```
