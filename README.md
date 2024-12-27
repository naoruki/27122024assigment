# 27122024assigment

1. What is the purpose of the execution role on the Lambda function?
   Execuation role of Lambda is IAM roles that grant permission for the function to access AWS services and resources during its execution.
2. What is the purpose of the resource-based policy on the Lambda function?
   Is an IAM policy attached to aws resource. It can controls who can access the specific resourse.
3. If the function is needed to upload a file into an S3 bucket, describe (i.e no need for the actual policies)
   - What is the needed update on the execution role? update the policy with S3 PutObject
   - What is the new resource-based policy that needs to be added (if any)?PutObject
