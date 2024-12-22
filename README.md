# LambdaFunctionForCD
This is aws lambda function for trigger shell script on build server , by passing value form event , event will get from s3 bukcet .

#pre req
1] build server have aws ssm agent instlled 
2] build server have IAM role which have policy of access s3 , and SSM 
3] Lambda function have IAM policy for access s3 , ssm 
