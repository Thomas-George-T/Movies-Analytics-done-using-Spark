![GitHub](https://img.shields.io/github/license/Thomas-George-T/MoviesLens-Analytics-in-Spark-and-Scala?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Thomas-George-T/MoviesLens-Analytics-in-Spark-and-Scala?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Thomas-George-T/MoviesLens-Analytics-in-Spark-and-Scala?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Thomas-George-T/MoviesLens-Analytics-in-Spark-and-Scala?style=plastic)

<p align="center">
	<a href="#">
		<img src="https://spark.apache.org/images/spark-logo-trademark.png" alt="Apache Spark Logo" width=275>
	</a>
	<br>
</p>


# Description
Using Spark to query Analytical questions on the [MovieLens dataset](https://grouplens.org/datasets/movielens/1m/) containing a million records using Spark. This features the use of Spark RDD, Spark SQL and Spark Dataframes executed on Spark-Shell using Scala API. We aim to draw useful insights about users and movies by answering a few basic questions.

## Environment
* Linux (Ubuntu 15.04)
* Hadoop 2.7.2
* Spark 2.0.2
* Scala 2.11

## Installation steps

1. Simply clone the repository
	```
	git clone https://github.com/Thomas-George-T/MoviesLens-Analytics-in-Spark-and-Scala.git
	```
2. In the repo, Navigate to Spark RDD, Spark SQL or Spark Dataframe locations as needed.

3. Run the execute script to view results
	```
	sh execute.sh
	```
4. The `execute.sh` will pass the code through spark-shell and then display the findings in the terminal from the results folder.

## Analytical Queries

### Spark RDD
1. [What are the top 10 most viewed movies?](/Spark_RDD/Top_10_Most_Viewed_Movies/)
2. [What are the distinct list of genres available?](/Spark_RDD/Distinct_Genres/)
3. [How many movies for each genre?](Spark_RDD/Movies_in_each_genre/)
4. [How many movies are starting with numbers or letters (Example: Starting with 1/2/3../A/B/C..Z)?](Spark_RDD/Movies_starting_with_Letters_or_Numbers/)
5. [List the latest released movies](Spark_RDD/Latest_movies/)

### Spark SQL
1. [Find the list of the oldest released movies.](/Spark_SQL/list_of_the_oldest_movies/)
2. [Create tables for movies.dat, users.dat and ratings.dat](/Spark_SQL/sparkdatalake/)
3. [How many movies are released each year?](/Spark_SQL/movies_each_year/)
4. [How many number of movies are there for each rating?](/Spark_SQL/movies_per_rating/)
5. [For each movie,](/Spark_SQL/5th_query/)
   [1. How many users have rated?](/Spark_SQL/5th_query/)
   [2. What is the total rating?](/Spark_SQL/5th_query/) 
   [3. What is the average rating?](/Spark_SQL/5th_query/)

### Spark DataFrames
1. [Clean data and convert into Dataframe.](Spark_DataFrames/)

> _**Note:** The results were repartitioned and stored into the same text file. It is highly recommended to not do this but it is done here for the sake of readability_

## Article Mentions
This project was featured on [Data Machina Issue #130](https://www.getrevue.co/profile/datamachina/issues/data-machina-issue-130-112552) listed at number 3 under ScalaTOR. Thank you for the listing

## License
This repository is licensed under Apache License 2.0 - see [License](LICENSE.md) for more details

