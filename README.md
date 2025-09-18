FFMPEG TUTORIAL

# 1. Convert Video
- Video -> video
+ ffmpeg -i video_in.mp4 video_out.flv ( convert to flv )

- Video -> audio
    ffmpeg -i video_in.mp4 sound.mp3 ( convert to mp3 )

- Audio -> audio
    ffmpeg -i sound.mp3 sound.wav

# 2. Change bitrate
## 2.1 Khái niệm bitrate
- Chỉ khối lượng dữ liệu truyền đi trong 1 thời gian nhất định
- Kbps, Mbps
- Bitrate càng cao -> hình ảnh, video càng rõ nét, mượt và tốc độ cao
                   -> dung lượng file càng nặng
- Resulotion ( là độ phân giải )

## 2.2 Change bitrate
- Change bitrate Audio
    ffmpeg -i sound.mp3 -b:a 96k sound_out.mp3

- Change bitrate Video
    ffmpeg -i

- Change bitrate Audio + Video
    ffmpeg -i









