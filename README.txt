Eslam Adel - Project1
Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.


1- S3 Bucket: to make a storage and upload the website files on it and set the Permissions to make it public.
2- IAM: to Secure Bucket and saw warnings about making bucket public.
3- Configure S3 Bucket: in a static web hosing (changing the index and error both to index.html).
4- Distribute Website via CloudFront: to deploying our website and changing the path to / which it means the root path and our domain we created in step1 finnaly the ID and let everything default then we get the domain value like domain.cloudfront.net and my is (d2349cov2ak85p.cloudfront.net).
5- Access Website in Web Browser: open any web browser and copy the url on it and type at the end of the link /index.html then the website will displays in your browser (https://semo-web.s3.amazonaws.com/index.html).
