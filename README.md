<h1 align="center">SPARK-EMR-DEV</h1>
<h4 align="center">demo various data ETL process via AWS EMR </h4>

<p align="center">
<!--- travis -->
<a href="https://travis-ci.com/yennanliu/spark_emr_dev"><img src="https://travis-ci.com/yennanliu/spark_emr_dev.svg?branch=master"></a>
<!--- PR -->
<a href="https://github.com/yennanliu/spark_emr_dev/pulls"><img src="https://img.shields.io/badge/PRs-welcome-6574cd.svg"></a>
<!--- notebooks mybinder -->
<a href="https://mybinder.org/v2/gh/yennanliu/spark_emr_dev/master"><img src="https://mybinder.org/badge_logo.svg"></a>
<!--- hit count -->
<a href="http://hits.dwyl.io/yennanliu/spark_emr_dev"><img src="http://hits.dwyl.io/yennanliu/spark_emr_dev.svg"></a>
</p>


## Scala Projects 
* [spark_emr_dev](https://github.com/yennanliu/spark_emr_dev) - Demo of submitting Hadoop ecosystem jobs to AWS EMR
* [spark-etl-pipeline](https://github.com/yennanliu/spark-etl-pipeline) - Demo of various Spark ETL processes
* [utility_Scala](https://github.com/yennanliu/utility_Scala) - Scala/Spark programming basic demo 

## File structure
```
# ├── README.md
# ├── athena            : athena query
# ├── build.sbt         : build.sbt build sbt dev env
# ├── config            : config for cres access AWS, 3rd party services
# ├── data              : sample data for script tes
# ├── doc               : ref docs
# ├── hive              : hive scripts 
# ├── project           : sbt project files 
# ├── pyspark           : pyspark code 
# ├── quick_start.sh    : help script run sbt/spark commands
# ├── script            : help script
# ├── src               : main scala spark ETL code
# ├── target            : compiled java file
# └── task_step         : json files define tasks at EMR
```

## Quick Start

- [quick_start.md](https://github.com/yennanliu/spark_emr_dev/blob/master/doc/quick_start.md)

## Prerequisites 

1. Modify [config](https://github.com/yennanliu/spark_emr_dev/tree/master/config) with yours and rename them (e.g. `aws.config.dev` -> `aws.config`) to access services like data source, file system.. and so on. 
2. Install SBT as scala dependency management tool 
3. Install Java, Spark 
4. Modify [build.sbt](https://github.com/yennanliu/spark_emr_dev/blob/master/build.sbt) aligned your dev env
5. Check the spark etl scripts : [src](https://github.com/yennanliu/spark_emr_dev/tree/master/src/main/scala) 

## Ref

- https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-build-binaries.html
