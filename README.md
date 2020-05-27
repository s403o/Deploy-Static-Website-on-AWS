# Deploy Static Website on AWS
* In this project, i will deploy a static website to AWS using S3, CloudFront, and IAM.

## Step-1
  * S3 Bucket: to make a storage and upload the website files on it and set the Permissions to make it public.
## Step-2 
  * IAM: to Secure Bucket and saw warnings about making bucket public.
## Step-3 
  * Configure S3 Bucket: in a static web hosing (changing the index and error both to index.html).
## Step-4 
  * Distribute Website via CloudFront: to deploying our website and changing the path to / which it means the root path and our domain we created in step1 finnaly the ID and let everything default then we get the domain value like domain.cloudfront.net [myWork](www.d2349cov2ak85p.cloudfront.net/index.html).
## Step-5 
  * Access Website in Web Browser: open any web browser and copy the url on it and type at the end of the link /index.html then the website will displays in your browser, [myWork](https://semo-web.s3.amazonaws.com/index.html).