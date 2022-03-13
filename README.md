# record-with-ffmpeg
screenrecorder with ffmpeg

# check audio PulseAudio using command
```pacmd list-sources|awk '/index:/ {print $0}; /name:/ {print $0}; /device\.description/ {print $0}'```

# run file
```
chmod +x rekam
./rekam output_name_file.mkv or ./rekam_fix output_name_file.mkv
```
