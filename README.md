# qtm350_project
This project examines the sensitivity of AWS Rekognition using images of actors in different roles with facial and physical transformations.

# How to open the files:
First, open the folder s3_bucket. Each folder in there is a bucket in s3. Download the four folders and upload it into AWS s3 buckets before loading the notebooks. There should be 4 distinctive buckets in Amazone S3 with the following name: 'jaredfacematch', 'christianfacematch', 'charlizefacematch', and 'projectvuadachi'. The s3_bucket folder also contains the mega dataframe. 

# The notebooks:
The notebooks come with description for each function. The first notebook, project.ipynb, tests AWS Celebrity Rekognition and Facematch for the photos in each bucket. The second notebook, making dataframe.ipynb, creates the mega dataframe with different variables. The last notebook, regression.ipynb, produces graphs with the data from the second bucket.  
