# The Python "os" module for files on AWS S3


This module tries to mimic the builtin python "os" module, but for files on AWS S3.

Example:
```
os.listdir(directory)
       ↓ 
s3os = S3OS(bucket_name)
s3os.listdir(directory)
```
