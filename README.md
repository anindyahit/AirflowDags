# AirflowDags
Contains sample scripts for dag definitions

After creating the dag definition, need to copy the dag definition files in the airflow home directory

 cp  ETL_Server_Access_Log_Processing.py $AIRFLOW_HOME/dags

To view if it copied:

airflow dags list

To start dag:
airflow dags unpause <dagname>

To pause dag:
airflow dags pause <dagname>

can be done using the WebUI as well
