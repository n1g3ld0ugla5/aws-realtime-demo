# aws-realtime-demo
AWS Realtime Demo

Makes the bucket
```
aws s3 mb s3://mmywonderbucket
```

List S3 buckets
```
aws s3 list
```
Remove an empty bucket
```
aws s3 rb s3://nigelseriousbucket
```
Create a Text file
```
cat > testFile.txt
```
Close with ```ctrl + C``` <br/>
<br/>
Move the test file into the new buckey
```
aws s3 cp testFile.txt s3://nigelseriousbucket/testFile.txt
```

Alternatively, delete the files in the bucket:
```
aws s3 rm s3://mmywonderbucket --recursive
```
