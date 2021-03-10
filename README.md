# ctfd-auto-backup
Tools for backing up CTFd DB (SQL) automatically

### How it works :
It's basically just grabbing the SSRF token and submit that with other credentials to export the backup file.

### Install the libraries :
```
pip install BeautifulSoup4
pip install requests
pip install wget
```
### Usage :
```
1. Change all the variables that contain url/domain to your CTFd url/domain
2. Run the script `python ctfd-auto-backup.py`
3. The files that have been downloaded will be in the backup_dir
4. You can put this script into a time-based job scheduler such as cron or any automation utilties that can run python in it
```
