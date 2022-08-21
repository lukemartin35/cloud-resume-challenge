# cloud-resume-challenge

This repo is mostly about my experience with cloud resume challenge by Forrest Brazeal

Currently I already done the following steps: 

Step 1: AWS Cert. Although I already have started step 2, I already have a 3 certs in MS Azure(Fundamentals, Administrator & Security Engineer). Why using AWS? Because that's my company is using & I was able to get promoted to DevOps/SRE role. 

I learned the basics of cloud because of Azure & I was able to "translate" Azure services to AWS like VM to EC2, Storage to S3, DNS to Route53 etc. Also that's where I learned that all cloud service providers will have a similar services like GCP, Linode, AlibabaCloud, Oracle Cloud and others.   

Steps 2-6: which is hosting my resume via S3 Bucket, Cloudfront, & Route53. 
For the resume itself I only stick with HTML5 since I have a problem with my CSS file not able to render properly on Cloudfront. For S3 bucket I was able to learned that there's an option to host static website without the use Route53 but leaving your bucket exposed to the public. For Route53 you can buy a .click domain for $3, recommended for those people like me wanted to use it for testing purposes & setting up A & CName. & For Setting up CloudFront for your 2 S3 buckets to make sure my website will be load fast anywhere in the world 



