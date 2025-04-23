This is a data-management assignment by IK (Interview KickStart).
It will demonstrate a data pipeline in Airflow that will accomplish
 - Download of Raw Dataset from Kaggle (Bash Operator)
 - Perform Feature Engineering on the Raw Dataset (PythonVirtualenvOperator)
 - Convert the Engineered Dataset to Parquet (PythonVirtualenvOperator w/TaskFlow API)
 - Convfigure the empty git/dvc repo and commit the datasets (PythonVirtualenvOperator w/TaskFlow API)
