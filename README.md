# Galaxy BIBBOX application

## Hints
* approx. time with medium fast internet connection: **5 minutes**


## Docker Images Used

 * bibbox/galaxy-proftpd
 * bibbox/galaxy-postgres
 * bibbox/galaxy-slurm
 * bibbox/galaxy
 * bibbox/galaxy-galaksio
 * busybox:latest

## Mounted Volumes

- /var/lib/postgresql/data
- /export/ftp
- /export/
- /local_tools
- /usr/local/apache2/htdocs/server/conf/