# caja-shrink-pdf
adds right click menu entries to shrink (compress) pdf and to secure delete files

by _mu

TO INSTALL
unpack the .tar archive into a folder, then
right click the file named "install" and make it executable. then double-click it and choose to execute it.

this will add:
"compress-pdf", "simple-compress-pdf" and "secure-delete" options to your context menu in Caja file browser

you might have to restart caja before they apear
you might have to install the following dependencies: ghostscript poppler-utils zenity libcanberra-gtk-modules

###

WHAT IS IT DOING?
it will install the files:
.local/share/file-manager/actions/compress-pdf.desktop
.local/share/file-manager/actions/simple-compress-pdf.desktop
.local/share/file-manager/actions/secure-delete
.config/caja/scripts/compress-pdf

into your $HOME folder

###

THE INSTALLER SCRIPT WILL NOT OVERWRITE EXISTING FILES. IF YOU NEED TO UPDATE THE SCRIPTS USE UNINSTALL SCRIPT FIRST.
