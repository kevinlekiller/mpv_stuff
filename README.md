# mpv_stuff
Random mpv stuff.

####mpvbd

This is a bash script to play blurays with mpv by passing the path of the bluray location.  
The path can be the main path to the bluray or any folder/file within the BDMV or CERTIFICATE folders.
The intention of this script is to be used with a file manager like Dolphin, associating .m2ts or .bdmv files.
Arguments other than the path are also passed to mpv.

Examples:  
`mpvbd /media/bluraydrive/`  
`mpvbd /media/bluraydrive/BDMV/index.bdmv`  
`mpvbd --fs --pause /media/bluraydrive/BDMV/`

####mpvrr

This is meant to be used while using [autospeed](https://github.com/kevinlekiller/mpv_scripts/tree/master/autospeed).  
autospeed can change the refresh rate of the monitor, although with vdpau some issues arise, like image corruption, this is why this exists.
