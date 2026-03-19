vidhub4.cc 调试时关闭间断点即可

```
ffmpeg -i "video_name.mp4" -c:v libx264 -preset medium -crf 18 -c:a aac -b:a 192k "video_name_pr.mp4"
```
