# caja-shrink-pdf v1.5 
# adds right click menu entries to shrink (compress) pdf and to secure delete files
# ABSOLUTELY NO WARRANTY OR LIABILITY FOR FILE LOSS - USE TO YOUR OWN RISK. USE ONLY AFTER UNDERSTANDING WHAT IT DOES
# by _mu
# LICENSE:	GNU GPL v3 (http://www.gnu.org/licenses/gpl.html)
# WEBSITE:	https://github.com/Aaaamu/caja-shrink-pdf.git OR DOWNLOAD ARCHIVE FROM https://webcloud.zaclys.com/index.php/s/5H6p4DoiUtO6PCi

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
.local/share/file-manager/actions/compress-pdf

into your $HOME folder

###

THE INSTALLER SCRIPT WILL NOT OVERWRITE EXISTING FILES. IF YOU NEED TO UPDATE THE SCRIPTS USE UNINSTALL SCRIPT FIRST.

### VERSIONS

v1.5
moved script .config/caja/scripts/compress-pdf to actions folder to avoid double appearance in context menue
left the scripts-folder in the repo for future use
