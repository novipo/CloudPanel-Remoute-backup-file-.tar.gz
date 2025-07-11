# CloudPanel-Remoute-backup-file-.tar.gz

This change allows for compressed backups of sites during remote server backups within CloudPanel.

Site folders under the /home directory are created with a .tar.gz extension, saving storage space.

After backing up the above files, replace them with the files from your server.

The files are located in the following paths:

/home/clp/htdocs/app/files/src/System/Command/TarExtractCommand.php
/home/clp/htdocs/app/files/src/System/Command/TarCreateCommand.php
/home/clp/htdocs/app/files/src/Command/RemoteBackupCreateCommand.php
