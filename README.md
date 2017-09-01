# mc-save-backup
backup your save file as you play

this bash script will start minecraft for you, upon closing it your save file will be compressed to a tar.xz file and moved to the backup location. before moving it test the sha of the current file and the latest backup to make sure that non changes aren't kept. 

## usage
* make sure the path to your minecraft directory is correct.
* change your backup location
* change your .desktop file or menu entry to point to the bash script instead of straight to the launcher
