# dbScripts
MySQL, import and export

## Backup

A backup is a dir name as TYPE-YYYY.MM.DD.HHMMSS, with sql file fo each table (dbname.tablename.sql).
The backup are first place in a process dir which you can define outside the dir where you keep all you backup.
e.g to make an rsync only on the complete backup.

- /backup path/
 - inprocess/
 - keep/
 - log/

### Configuration


## Import

Import or Restore a backup.
To import in parallel, cut in several type and/or database

### Configuration
