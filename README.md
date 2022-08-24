# ChangeDataCapture-using-Azure-Data-Engineering-

#Context:-
Imagine, you are working for a Health system, where they want to process data from a source Database like Oracle Database server however, you are not permitted to access the underlying table directly. You are expected to ingest the data from an output of a real time Change Data Capture Tool like Qlik Replicate. The business request here it to process the data outputed in a data lake in near real time. Performing both full and incremental load.

#Prerequiste tools needed:-
#Azure Data lake Gen 2
#Data factory
#Azure Synapase SQL pool

The goal is to build an ETL pipeline that can process both full and incremental load from the Data lake folder source table and load to the target SQL table

#Project assignment:-
Build an ETL pipeline using Data factory that reads first the full load loads it into the Target SQL db table
Read the incremental file and process and load into the Target SQL table.
Final Target table should look like the below:--
![175101501-12abfbd2-34f1-4872-b5b1-be5e5418a2c4](https://user-images.githubusercontent.com/67510391/186425285-47b42c24-c4f9-4f23-9415-0a0a61a0c245.png)


![183940348-d5762b6b-b45d-446e-9357-dd7527b7f78d](https://user-images.githubusercontent.com/67510391/186425492-a7d7a71c-533e-4a07-8422-f931b35f4830.png)
