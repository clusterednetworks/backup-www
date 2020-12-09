# backup-www
Bash Shell Script to Backup Webroot on Webserver
Performs a full backup of the website document root and creates a tar file for each site. 
Be sure to edit the configuration options at the beginning of the script to match your environment prior to executing.
The end result will be a TAR archive of each website with the name '(current-datestamp)-website-dir-backup-tar.gz'. 
For Backing up your Website Databases please see our Backup MySQL script.

# Usage:

1. Pull up a terminal or SSH into the target server.

2. Logon as root

<code>sudo -i</code>

3. Download the installer script.

<code>wget https://raw.githubusercontent.com/clusterednetworks/backup-www/master/backup-www.sh</code>

4. Edit the configuration options at the beginning of the script to match your environment prior to executing.

5. Make the script executable

<code>chmod +x backup-www.sh</code>

6. Run the script.

<code>./backup-www.sh</code>

8. Setup a cronjob to run the script daily/weekly if you choose.
