# rPlayer

rPlayer is a video and image application built on the public rasterm C++ API. It owns all multimedia concerns:

- OpenCV image/video decoding and scaling
- FFmpeg audio demuxing, decoding, and resampling
- Miniaudio playback
- Audio master frame timing and late frame dropping
- Adaptive playback resolution
- CSV performance metrics

It does not include or reach into rasterm's private `src/` modules. The Visual Studio project is `rPlayer.vcxproj`, and its Release output is:

```text
apps/rPlayer/build/Release/rPlayer.exe
```

This directory is an application consumer and is not installed with `rasterm::rasterm`.
