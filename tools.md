#### ffmpeg
- 利用 ffmpeg 截取视频
    - ffmpeg -i <input_video> -ss <start_time> -t <duration> -c copy <output_video>
        - -i 表示要操作的视频
        - -ss 表示开始截取的时间
        - -t 表示截取出来的视频持续的时间