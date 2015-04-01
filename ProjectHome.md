dba-lz4 added the lz4 compression algorithm to the original PHP dba extension and was transparent to the up-level applications.


This extension was built based on the dba code extracted from original PHP 5.4.6 source and does not provide any app-level options to tune the compression algorithm. You can open and edit dba.c at line 581 or 582 to choose the preferred compression level.




Please download the package at http://code.google.com/p/php-dba-lz4/downloads/list


For lz4, please visit http://code.google.com/p/lz4/


Note: This extension was built within about only 30 minutes and was NOT tested too much so you're using it at your own risk. dba-lz4 can only deal with databases created with itself, cause the data were from different format at all (compressed with lz4)


Any feedbacks are welcome, please contact blueflycn#gamil.com. Thank you all