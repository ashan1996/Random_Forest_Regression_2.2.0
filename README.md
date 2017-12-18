# Random_Forest_Regression_2.2.0/2.1.0
Use the ml libraries and MLlib libraries
This program show how Random Forest Regression Model works in scala.I have used common dataset to train the trees called "
Auto MPG Data Set ". You can directly access the dataset using the url I mentioned below. There are two diferent programs to achive random 
forest. If you use this you have to change the file location and give the correct file as the input. I recommended you 
to use intelij Idea ide. sbt version scala version and etc. must be compatible. If not you cannot achive the goal.
Use the following dependencies to build your project

version := "1.0"

scalaVersion := "2.11.0"

libraryDependencies += "org.apache.spark" % "spark-core_2.11" % "2.2.0"

libraryDependencies += "org.apache.spark" % "spark-sql_2.11" % "2.2.0"

libraryDependencies += "org.apache.spark" % "spark-mllib_2.11" % "2.2.0"

URL - https://archive.ics.uci.edu/ml/datasets/auto+mpg
