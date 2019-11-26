


Data Mining
###################################################



|
|


**What is this ?**  

The following github repo contains detailed information about Data Mining


|
|


.. contents::

.. section-numbering::


|
|
|





References
=============


|


Links
---------------



* `Gitbook Internals of Apache Spark   <https://jaceklaskowski.gitbooks.io/mastering-apache-spark/>`_
  — really really good overview of how Apache Spark functions



|
|




Book
-------------


* `Ch 1 <http://umich.summon.serialssolutions.com/2.0.0/link/0/eLvHCXMwpV1LS8NAEB60uShCfdJorUH0mLLZ5ulFtG0Qsbei3pZNdiPFGsSk4s93No82VNCDl0DIkmVnk2_n-Q0AXcODSPFIz3LT6i_exBwvlRPNHDheYKoOccpRMHqgN6FzHw4aBENFvLBKUuzXSLmKpKoXzV54WmVb9stKgGtRoDMqjUTVV2vUwVO9BRrC_HiydL8Q1IMQnAuSHXVq2V5QMUAt761t2ObZK2IN4lCeNQKZTV1UFY8sssaZFLahjv-WmSgF5VO96J9kj_9f5C5oUlVG7MGGTPehXfeDMCp4OICLEc-5MSlaTlwZw7IgMjN4KoxpTRWbHcJTOJ4O78yqC4PJla6GP5IvRBLFqiU9SbwgRgVQkCiKJWKBi7htDyLuRZaVSIvjQD9Rp35CXdRMfE9GqAMdwQ5X-fppXtT1iQ4YMnY46h6CBNK3Len5Duc84q4XC4k2JtfhvCF79jkvxJSx1Qb5xNOhW24Jey-pOdYfn9XyZE0ps_HtkKKZatHfRpSy1aFT7vByCrTB0G51qa3D5fojllFGmO-o8K-i0ndY_pUf_znJCWyVrmrXJEEXWvnHQp6CVux9DzbNx-de9f1-A6nuAfs>`_
  — Chapter 1 of Data mining: concepts and techniques. Han, J., Pei, J. and Kamber, M. (3rd Edition)



* `Ch 1 <https://ebookcentral-proquest-com.proxy.lib.umich.edu/lib/umichigan/detail.action?docID=729031>`_
 



|



Add
=====================

* a
* b
* c




|



Notebooks
=========================================

As progression is made step-by-step, I will upload pertinent jupyter notebooks.  This is the key to really understanding this complicated approach. 

|

Jupyter Notebook Links
------------------------

The following are working jupyter notebooks as I dive deeper into Apache Spark, Databricks, etc.  All raw .ipynb notebook files are contained under ENTER/working_notebooks repo folder.  Most of the links below are enabled via nbviewer to show the notebooks in html, to aid ease of viewing...


|


* `Databricks Overview notebook <https://rawcdn.githack.com/TomBresee/The_Spark_Genome_Project/4602f11ee09c4c08f8844f57ae6aaca9f9858470/ENTER/working_notebooks/overview_001_f.html>`_
  — **Start Here**  


|



* `Databricks 101 <https://nbviewer.jupyter.org/github/TomBresee/The_Spark_Genome_Project/blob/master/ENTER/notebooks/001-pyspark.ipynb>`_
  — for introductory example of how to create RDD datasets and get familiar with the Databricks platform



|


* `Hail running on Apache Spark running on Ubuntu <https://nbviewer.jupyter.org/github/TomBresee/The_Spark_Genome_Project/blob/master/ENTER/working_notebooks/HAIL%20on%20Apache%20Spark.ipynb>`_
  — successful implementation of Hail 0.2 on Apache Spark (Ubuntu-based), working example (notebook kept in the 'working notebooks' sub-folder under /ENTER)



|


* `Hail running on Databricks Apache Spark written in Scala <https://nbviewer.jupyter.org/github/TomBresee/The_Spark_Genome_Project/blob/master/ENTER/working_notebooks/hail_databricks.ipynb>`_
  — successful implementation of Hail 0.2 on the Databricks platform in Scala code  


|

|


Advanced Notebooks
------------------------

These are bit more complex, include things like Delta Lake, etc. 


|



* `Databricks Overview notebook <https://rawcdn.githack.com/TomBresee/The_Spark_Genome_Project/4602f11ee09c4c08f8844f57ae6aaca9f9858470/ENTER/working_notebooks/overview_001_f.html>`_
  — **Start Here**  






|
|
|



References
=============


|


Apache Spark
---------------


* `Apache Spark Website <https://spark.apache.org/>`_
  — the core website for Apache Spark 


* `Apache Spark Documentation <https://spark.apache.org/docs/latest/>`_
  — the main documentation link 

* `Hadoop <https://hadoop.apache.org/>`_
  — Hadoop Standard Library



|



Databricks
-------------


* `Documentation <https://docs.databricks.com/>`_
  — the main documentation link for Databricks


* `User Guide <https://docs.databricks.com/user-guide/index.html>`_
  — the main user manual for Databricks


* `Github Delta Lake  <https://github.com/delta-io/delta>`_
  — github location


* `Connecting MySQL Workbench <https://docs.databricks.com/user-guide/bi/workbenchj.html>`_
  — Connecting org.apache.hive.jdbc.HiveDriver driver definition  


* `Hipster Scala Example <https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8497971343024764/53198984527781/2559267461126367/latest.html>`_
  — Scala example with variant spark


* `Databricks Connect  <https://docs.azuredatabricks.net/user-guide/dev-tools/db-connect.html>`_
  — direct CLI access to the instance


* `Spark Definitive Guide <https://github.com/databricks/Spark-The-Definitive-Guide>`_
  — github location of the book `Spark - The Definitive Guide' that can also be run in Databricks via the DBFS location:  dbfs:/databricks-datasets/definitive-guide/data




|

Genomics
-------------


* `Hail Scala Genomics ETL Tutorial <https://lamastex.github.io/scalable-data-science/sds/2/2/db/999_05_StudentProject_HailScalaGenomicsETLTutorial.html>`_
  — Written by Dmytro Kryvokhyzha, excellent overview of using Databricks in Scala with Hail



|

Scala
--------


* `Scala <https://www.scala-lang.org/>`_
  — the main website for Scala.  There is no getting around it.  You want to push the envelope, you must learn Scala...



|

Hail 0.2
--------


* `Hail Site <https://hail.is/>`_
  — core page for Hail

  
* `Hail on AWS EMR  <https://github.com/hms-dbmi/hail-on-EMR>`_



|

Next Generation DNA Sequencing (NGS)
---------------------------------------


* `Genetic Data VCF BAM FASTQ  <https://us.dantelabs.com/blogs/news/genetic-data-fastq-bam-and-vcf>`_
  — The big picture view of the file format options and their place in sequencing

* `Databricks Unified Analytics Platform for Genomics <https://github.com/TomBresee/The_Spark_Genome_Project/raw/master/ENTER/txt_based_info/Unified_Analytics_Platform_for_Genomics_Databricks.pdf>`_
  — Blueprint data for new Databricks Genomics platform 



|





Modify and Upload 
-------------------


* `error message  openCostinBytes  <https://stackoverflow.com/questions/49048212/how-to-set-spark-sql-files-conf-in-pyspark>`_





|
|
|
|



