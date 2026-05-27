
# Task 3: Audio-Video Merging

## Objective
Merge audio with reconstructed video using FFmpeg.

## Command Used
ffmpeg -i output.mp4 -i audio.mp3 -c:v copy -c:a aac -shortest final_video.mp4

## Description
Audio track was merged with video to create final output.

## Audio Source
https://pixabay.com/music
