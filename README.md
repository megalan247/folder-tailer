# folder-tailer

This application will take a folder as an argument and then watch all files in that folder for new lines, then write out these lines to the console.
Kind of like multitail but doesnt require any TTY, and is much dumber.

# Usage

This will tail all files in /var/log for new lines and watch for new files.

`./folder-tailer /var/log`
