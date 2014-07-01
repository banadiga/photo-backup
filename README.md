Photo backup
============
Script create backups of photos.

Photos extension: BMP, bmp, JPG, JPEG, Jpg, jpg, NEF, nef, PNG, png, TIF and tif

Structure of photos directory:
* **year** - year in format *YYYY*
* **mounth** - mounth in year in format *YYYY.MM.DD SOME TEXT*


Install
-------
Script use ant and zip.
* Install Apache Ant:
```
$ sudo apt-get install ant
```
* Install zip:
```
$ sudo apt-get install zip
```
* Clone script:
```
$ git clone git@github.com:banadiga/photo-backup.git
```

Configuration
-------------
Change backup.properties file.
* **src.dir** - path to folder with photos directory.
* **zip.password** - password of zip file.
* **split.size** - split zip file size.
* **years** - list of years.
* **date.separator** - mounth separator.
* **target.tar.dir** - target directory for tars file.
* **target.zip.dir** - target directory for zips file.
* **target.sum.dir** - target directory for sums file.

Run
---
* Run as ant script
```
$ cd ./photo-backup
$ ./ant
```

* Run as shell script
```
$ cd ./photo-backup
$ ./run
```
