# Solar-eclipse-image-aligning

This is a straight-forward script to ingest a directory of JPG photos of a partial solar eclipse and output a set of cutouts centered on the sun's center.  These are the following key steps:

1) ingest image file
2) identify minimum and maximum illuminated pixels in the image
3) use any three points to calculate the sun's central position
4) export an image centered on that point

Because I then went on to use ffmpeg to generate an mp4 file, I did not have a file export preference, nor did I have compunctions about discarding the few images where the sun was off-center enough that the cutout region went beyond the image boundaries
