Django DB Backend for SAP HANA
----------------------------
Under Development

Log
------
connects to db

uses the settings_dict['NAME'] as default schema

syncdb creates tables, sequences and indexes

Simple inserts work

Major problem is the paramstyle hdb supports qmark while django assumes %s, need to write a converter

Disclaimer
--------------
This project is not a part of standard SAP HANA delivery, hence SAP support is not responsible for any queries related to
this software. All queries/issues should be reported here.
