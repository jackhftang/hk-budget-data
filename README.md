# hk-budget-data

## usage

  1. modify the year you want to download
  2. remove lines in catalog.txt if you not want to download
  3. `sh download`

## Note

  1. catalog.txt is extracted from catalog of 2014. 
     Some catalog like summary are supposedly removed.
     But the catalog may potentially not complete for 
     years before 2014.

  2. If you want english version, uncomment the line 
     `lang=eng` and then run again.

  3. rerun download if the symlink do not work. 
     (it will not download files if files already exist)

  4. by the way, downloading from gov server is actually 
     quite fast. =]