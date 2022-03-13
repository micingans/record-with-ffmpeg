# record-with-ffmpeg
screenrecorder with ffmpeg

# check audio PulseAudio using command
```pacmd list-sources|awk '/index:/ {print $0}; /name:/ {print $0}; /device\.description/ {print $0}'```
