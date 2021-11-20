# Reciva stations as SQLite database

This is a dump of Reciva stations database which no longer exists. It contains 65859 streams for 52754 internet radio stations collected by users.

**20.11.2021 - Added 56102 new streams and 44060 stations (however most of them are old and probably offline)**

This database is meant only to be used to add channels to your "bricked" Reciva-based radios (see https://github.com/jisotalo/reciva-radio-patching). It's not allowed to be used in any other purpose.

Another mirror for the stations.db file:

https://bayfiles.com/H909ldW3u0/stations_db

## How to use
1. Open the `stations.db` file with DB Browser for SQLite (https://sqlitebrowser.org/)
2. Open tab `Browse Data`
3. Select `station_view` view as table
4. Use filters to filter by different keywords, like `jazz`, `finland` etc.
5. The `stream_urls` contains all urls to that radio station separated by semicolon (;) 

![image](https://user-images.githubusercontent.com/13457157/133919343-4508ddb8-60f9-42ee-b981-70a4d76e9239.png)
