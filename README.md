# bigdata-P2-Scala-Spark-App

## Project Description
CLI Application for generating eCommerce data and performing analysis with Spark SQL, also implementing the Visualization

## Technologies Used
- IntelliJ IDEA version 2022.1.2
- sbt	version 0.1.0-SNAPSHOT
- Scala version 2.11.12
- Spark-core library version 2.4.1
- Spark-SQL library	version 2.4.1
- Vegas library	version 0.3.11
- Vegas-Spark library version 0.3.11
- Windows binaries for Hadoop version 2.7.1

## Features
- Random data generator
- SparkSession for SparkSQL queries
- Command Line Interface menu
- User Login
- Data visualization with Vegas

## Getting Started
My team used a stand-alone Spark environment in IntelliJ. 
You will need to download Scala and the Hadoop binaries for windows. 
The steps for the Hadoop binaries are listed here:

#### Download Windows binaries for Hadoop version 2.7.1
- Look for winutils.exe
- My team used this Github repo the download: https://github.com/steveloughran/winutils/tree/master/hadoop-2.7.1/bin

#### Place winutils.exe in its own folder in your C drive
- C:\\hadoop\bin\winutils.exe

#### Add Windows binaries for Hadoop version 2.7.1 to your Windows Environment Variables.
- Go to your Windows System Settings
- Type "environment variables" into the search bar
- When prompted, add the following to both User and System variables:
- Variable: HADOOP_HOME 
- Value: C:\\hadoop

## Contributors
- Abnel Negron https://github.com/Abnel-Negron
- Normand Jean https://github.com/CosmicStarr
- Tony Wilkins https://github.com/tonywilkins21
- Sherrell Jones https://github.com/Shjones502
