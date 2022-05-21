# How to upscale video to 720p

```bash
ffmpeg -i in.mp4 -vf scale=-1:720:flags=lanczos -c:v libx264 -crf 21 out.mp4
```

- `-i in.mp4` - input video file
- `-vf` - apply specific video filters
- `scale=` - scale video
- `-1` - width will be automatically calculated based on aspect ratio
- `720` - set scaling height to 720 pixels
- `flags=lanczos` - use `lanczos` [scaling algorithm](https://ffmpeg.org/ffmpeg-scaler.html)
- `-c:v libx264` - use H.264 codec
- `-crf 21` - use good quality for encoding
- `out.mp4` - resulting video file

group: upscale


link_youtube: https://youtu.be/jkjvXlwteVw
