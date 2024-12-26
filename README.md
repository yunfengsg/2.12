# 2.12
Given a Lambda function that is triggered upon the creation of files in an S3 bucket, answer the following:
1. What is the purpose of the execution role on the Lambda function?
   answer:grants the function permissions to access AWS services and resources.
3. What is the purpose of the resource-based policy on the Lambda function?
   answer:used to control access to the function by specifying who or what can invoke it.
5. If the function is needed to upload a file into an S3 bucket, describe (i.e no need for the actual policies)
What is the needed update on the execution role?
A: Limiting the permissions to the specific bucket
What is the new resource-based policy that needs to be added? To which resource?
A: Grants the s3:PutObject permission. Adding this policy ensures that the Lambda function’s execution role

