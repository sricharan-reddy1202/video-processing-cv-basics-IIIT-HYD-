
# Task 2: Video Reconstruction

## Objective
Convert extracted frames back into a video.

## Command Used
ffmpeg -framerate 30 -i frame_%04d.png -c:v libx264 -pix_fmt yuv420p output.mp4

## Description
1800 frames (30 fps × 60 sec) were used to reconstruct the video.

## Output Video
(uploaded video)
