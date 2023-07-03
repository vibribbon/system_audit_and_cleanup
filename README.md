# system_audit_and_cleanup
A terminal script to perform a quick system file audit. 

All scripts are without any kind of warranty, use entirely at your own risk!

On linux place into /user/local/bin/ and change permissions as follows: 
sudo chown root /user/local/bin/system_audit_and_cleanup.sh 
sudo chmod 755 /user/local/bin/system_audit_and_cleanup.sh
sudo mv /user/local/bin/system_audit_and_cleanup.sh /user/local/bin/system_audit_and_cleanup

Dependancies: none

This terminal script will search for combinaitons of files / folders mostly within the /home directory that are potentially of interest / concern.  These include public (777) files, non-root executable files, large files, duplicate files, manually installed apps, empty files & folders.
Recommended to pipe the output into a file, then remove the comments from lines where files / folders / apps are to be removed and run as an executable script.
Please make sure you check THROUGHLY and CAREFULLY before removing any files / folders / apps.

Issues:
Please note that the script does not currently provide a quick method for removing duplicate / large files or services, these need to be removed independantly.

END
