# Access-S3-objects-using-CloudFront
This is a simple demonstration on accessing the objects present in S3 using CloudFront to overcome the latency

# Architecture:
![image](https://github.com/rakshitasupadhya/Access-S3-objects-using-CloudFront/assets/107621546/ee687a01-97ed-4d66-bf30-ff1656ce386e)

# Implementation

1. Create a S3 bucket by enabling Public Access and upload a image in bucket
2. Access image from S3 bucket  (Note the response time)
3. Create a CloudFront Distribution
4. Access the image using Distribution Domain Name URL and note the response time 	
