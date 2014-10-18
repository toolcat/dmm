dmm
===

Dual movie maker

ffmpeg -y -itsoffset 0 -i hu.avi -itsoffset 0 -i eng.avi -c copy -map 0:v:0 -map 0:a:0 -map 1:a:0 out.avi
