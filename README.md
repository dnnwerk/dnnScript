# dnnTurbo Scripts - improving your DNN Database
## dnnTurbo Scripts are a set of SQL scripts, which improve stability and performance of DNN Platform (aka DotNetNuke)

dnnTurbo SQL Scripts are designed to improve stability and performance of the database used by your DNN websites. This is achieved by improving the database schema (fixing issues, enforce referential integrity and improving indexes) and the code to query it (using calculated columns, indexed views and improved functions and procedures). The schema remains fully compatible with DNN default schema, however, you'll have to run TurboUnschema.sql prior to any DNN upgrade, to remove schema binding from several functions and views.

The scripts are currently available for all DNN Platform versions 7.1.2 up to current release. 

Version 0 of the TurboDNN package consists of a number of prepared SQL files for DNN, please refer to readme.html for instructions.

If you have questions, please use discussion forum.

If you encounter a bug, please report on issues page.

This project is under active development for best performance of your DNN platform.
