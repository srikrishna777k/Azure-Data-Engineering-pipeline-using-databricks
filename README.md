# Data Engineering pipeline for Formula 1 analysis using Azure databricks

Multiple files of disparate data types are fetched from Ergast API and manually loaded into ADLS raw layer. The data is then taken and processed using Databricks notebooks and ingested into the processed layer in parquet format. Similarly the data is transformed into the presentation layer. The data is further analysed using Databricks notebooks and dashboards. The project is then replicated by using delta lake instead due to its benefits. The project is built for production quality through scheduling and monitoring. Moreover other solutions are also analysed to improve the project.

![image](https://github.com/srikrishna777k/Azure-Data-Engineering-pipeline-using-databricks/assets/75556669/8fba50fd-6767-4ca4-a3c2-a3aa3e5c6b98)

