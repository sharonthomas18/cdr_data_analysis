# cdr_data_analysis
Call Data Records (CDR) analysis done using Python 3.7.1 to determine useful behaviour from large amounts of raw data.

A dataset (approximately 320 MB in size) is available to download at the following link:
https://www.dropbox.com/s/pv2u87mwruesaxc/CDR%20set.csv?dl=0
which represents a subset of inter-subscriber voice calls covering a period of several months in the African country of Chad. Each entry in this file represents a single call and contains four parameters as shown in the example below:

7bc65f6f4342d49242514a50ce53d71d 555af6d82bb7f4c7475f7af29e8db147 29/02/2016 23:51:00

The four parameters are separated by a white space character and represent:
 Hash of MSISDN of calling party in the call
 Hash of MSISDN of called party in the call
 Date on which the call started
 Time at which the call started

