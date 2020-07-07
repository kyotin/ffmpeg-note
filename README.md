# ffmpeg-note
Note some ffmpeg runable code

# How to run transcode
Compile it first
```
gcc -g new_transcoding.c -lavcodec -lavformat -lavfilter -o transcoding 
```

Then run it
```
./transcoding /Users/tinnguyen/Downloads/test.mp4 test.mp4
```
