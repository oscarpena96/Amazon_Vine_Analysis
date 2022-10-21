# Amazon_Vine_Analysis

You might know amazon as the website that sells everything and it gets to your door but that´s not even the tip of the iceberg from this megacompany, it has a lot of services and now with the explosion from technology amazon didn´t stayed behind creating Amazon Web Services (AWS) a lot of commpanies depend on it to be able to satisfy their client, this is due to amazon relational database service, it comes for a small price and it´s really helpfull to developers all over the world, it allows you to conect to your database in an easy way.
They offer a lot of different datasets for developers to practice and on top of that they have the 1 year free tier AWS, it has some limitations but you are able to practice and do as you need to be able to learn.

# Materials
- Jupyter Notebook
- Spark
- SQL
- Python
- AWS RDBS

# Objective
Use one of the datasets from S3 to understand Spark and how to use it, process data and perform ETL on the dataset, upload data to AWS and use one of the three options (Pandas, Spark, SQL) to gain knowledge that clients may have.

# Results
The process was easy, obtaining data from different sources is a must have skill in all data analyst or any rammification, from there the schema was printed to see what type of data there was, after looking at it almost all the data was correct with the exception of date.

![obtain_data](https://user-images.githubusercontent.com/100168991/197097661-1c4d9d2e-81cb-4add-bc50-365754f44235.png)

but it was a walk through the park transforming data at this point.

![to_date](https://user-images.githubusercontent.com/100168991/197097791-0b09d141-4ab9-485c-8281-8ac9397e0b96.png)

After creating 3 different dataframes they upload it to AWS and extracted with PostgreSQL for further examination, with a csv file the vine reviews where imported to Jupyter Notebook and the data was cleaned to finish with 2 dataframes, the first one for vine reviewers and the second one with non-vine reviewrs, lastly the question who gives more 5 stars was answered, non-vine reviewers tend to give more 5 star reviews with a 58% and vine reviewrs do it 52%, there is not a lot of difference but still there can be some statistical prrof behind it
