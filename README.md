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

####mpvpnc

Disables the compositor on plasma 5 when starting mpv, sets back the compositor when exiting.  
Only disables/re-enables the compositor if it was already enabled.

Examples:  
`mpvpnc /path/to/file --pause --start=1:01`
