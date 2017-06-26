Please refer ReadMeFile.docx for detail description 

Creating/deleting/uploading a file to s3bucket from command line using python boto3


•	S3bucket.py is my python file I have created, which takes two arguments.


1)	a)Before Creating  s3 bucket :
 
  b) After creating s3 bucket :
command : ./s3bucket.py create-bucket sravan_first_510

First argument: create_bucket
Second argument: Unique_bucket_name
  

2)	Uploading a new file to bucket :
Command :  ./s3bucket.py upload-object sravan_first_510

First argument: upload-object
Second argument: Unique_bucket_name

 

3)	Deleting s3bucket :
Command : ./s3bucket.py delete-bucket sravan_first_510

First argument: delete-bucket
Second argument: Unique_bucket_name

 


