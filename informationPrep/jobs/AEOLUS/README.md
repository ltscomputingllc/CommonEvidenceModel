AEOLUS staging data load process
=========================================

Background
----------
This is the AEOLUS staging data load process.
The 2 source data files are created as the output from the AEOLUS ETL process, see the below github repo for details:
[AEOLUS github repository](https://github.com/ltscomputingllc/faersdbstats)

Table(s) loaded
---------------
staging_aeolus tables

Instructions
------------
1. Place the below two files in the FILE_DIR directory and verify that the FILE_NAME1 and FILE_NAME2 job variables are set to those file names:

standard_drug_outcome_statistics.csv
standard_drug_outcome_contingency_table.csv

2. Load the Pentaho job in the Pentaho Spoon client.
3. Run the job.

