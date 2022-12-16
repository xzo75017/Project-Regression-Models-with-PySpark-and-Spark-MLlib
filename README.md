
# I Spark ML

- With the increase in data sizes and various sources of data, solving machine learning problems using standard techniques pose a big challenge 
- Spark is a distributed processing engine using the MapReduce framework to solve problems related to big data and processing of it
    
# II Pyspark
PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.  

## III Machine Learning

- Machine learning (ML) is the study of computer algorithms that can improve automatically through experience and by the use of data

# IV Need Of Spark ML
- When data is huge we need to use spark MLlib  

# V Types of Learning  
- Supervised Learning
- UnSupervised Learning

# VI Data Pre-Processing

- Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model

# VII Regression Algorithms 
- Linear Regression 
- Multi linear Regression 
- Random Forest Regression



# VIII Business Overview Of Airlines Industry

- https://openflights.org/
- https://developer.ibm.com/exchanges/data/all/airline/
- https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics

# IX S3 link for dataset

- s3://airlines555/airline/data.zip


# X Code Description
    File Name : Linear_Regression.ipynb, Multi_Linear_Regression.ipynb,   
                Random_Forest_Regression.ipynb ,  
                Linear_Regression.py, Multi_Linear_Regression.py  
                and Random_Forest_Regression.py  
    DataSets : data.zip  
    File Description : Implement Spark MLlib algorithms  
    
## Steps to Run
There are two ways to execute the end to end flow.  
- Command Prompt => python script
- spark_path spark-submit file_path
- spark_path => <path_to_spark>>
- file_path => <path_to_file>
- Data file path is same as script file path

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\sparkml\Linear_Regression.py>  


- IPython

### Modular code
- Create virtualenv
- Install requirements `pip install -r requirements.txt`
- Run Code `python Linear_Regression.py`
- Check output for all the visualization
### IPython
Follow the instructions in the notebook `Linear_Regression.ipynb` 
