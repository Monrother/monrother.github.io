#### ffmpeg
- 利用 ffmpeg 截取视频
    - ffmpeg -i <input_video> -ss <start_time> -t <duration> -c copy <output_video>
        - -i 表示要操作的视频
        - -ss 表示开始截取的时间
        - -t 表示截取出来的视频持续的时间

#### shell
- shell 想将 stdout 和 stderr 都输出在同一个文件的方法是 2 > &1
- tar
    - 解压 tar 包时可以通过 -C 选项指定解压目录。
