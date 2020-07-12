# s3-scripts

Dumping my s3-cmd scripts here

# s3-md5

Used to validate file uploads to s3.

For each file in current working directory:

1) Calculate md5 checksum
2) Get md5 sum for an object corresponding to the filename.
    * md5 sum of the object is not calculated, byt fetched from the object metadata
3) Compare the file checksum with the object checksum
4) Print results
