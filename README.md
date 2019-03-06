# README.md
#
# https://github.com/pelicanbill/numbered_frames
#
An .avi test file full of 500 grey frames 800x600 pixels. Each has a sequential number on it and a coloured circle in a different position

This is primarily designed to test frame processing programs. I found that I was losing some frames which were being read by a thread and picked off a queue by another thread, so I created this test file to fill up my queue with these frames to find out where the problem was happening. As the frames are read sequentially, they should each have a sequential number on them. Any discrepancy can easily be noticed.
