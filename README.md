# mpv_stuff
Random mpv stuff.

####mpvssh

Bash script for listing videos from a SSH server's directory,
plays them when you type in the number and press enter.
Change settings in the script for your SSH server's location and username.
Optionally pass regex to search, for example:
`./mpv_ssh 2002`         ; will search for videos with "2002" in the file name.
`./mpv_ssh 1080p.*h264`  ; will search for videos with 1080p followed by h264 in the file name.

####mpvbd

This is a bash script to play blurays with mpv by passing the path of the bluray location.  
The path can be the main path to the bluray or any folder/file within the BDMV or CERTIFICATE folders.
The intention of this script is to be used with a file manager like Dolphin, associating .m2ts or .bdmv files.
Arguments other than the path are also passed to mpv.

Examples:  
`mpvbd /media/bluraydrive/`  
`mpvbd /media/bluraydrive/BDMV/index.bdmv`  
`mpvbd --fs --pause /media/bluraydrive/BDMV/`
