# Reciva stations as SQLite database

This is a dump of Reciva stations database which no longer exists. It contains 8192 streams for 7555 internet radio stations collected by users.

**NOTE: Just noticed that at least UK stations are missing... If you happen to have the full backup, please let me know**

This database is meant only to be used to add channels to your "bricked" Reciva-based radios (see https://github.com/jisotalo/reciva-radio-patching). It's not allowed to be used in any other purpose.

## How to use
1. Open the `stations.db` file with DB Browser for SQLite (https://sqlitebrowser.org/)
2. Open tab `Browse Data`
3. Select `station_view` view as table
4. Use filters to filter by different keywords, like `jazz`, `finland` etc.
5. The `stream_urls` contains all urls to that radio station separated by semicolon (;) 

![image](https://user-images.githubusercontent.com/13457157/133919343-4508ddb8-60f9-42ee-b981-70a4d76e9239.png)
