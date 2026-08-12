# rPlayer

rPlayer is a video and image application built on the public rasterm C++ API. It owns all media concerns:

- OpenCV image/video decoding and scaling
- FFmpeg audio demuxing, decoding, and resampling
- Miniaudio playback
- Audio master frame timing and late frame dropping
- Adaptive playback resolution
- CSV performance metrics

Download & move the project to rasterm's `apps/rPlayer` directory. You can build the project with `rPlayer.vcxproj` via vs2022 or `build-rplayer.ps1` via cmake, and its output is:

```text
apps/rPlayer/build
```