# Host Static website on AWS S3
# Table of Contents
- [Description](#description)
- [Prerequisites](#prerequisites)
# Description
This is a simple static website hosted on AWS S3 bucket. The website is created using HTML and CSS. The website is hosted on AWS S3 bucket and the endpoint URL is used to access the website.
# Prerequisites
- AWS account, you can get free tier account [here](https://aws.amazon.com/free/)
- Clone the repository ``git clone https://github.com/julienawonga/static-website-on-aws-s3.git
  ``

# Steps
## Create S3 bucket
- Create S3 bucket with the name desired (the name must be unique across all existing bucket names in Amazon S3)
- Select the region where you want to create the bucket
- Uncheck the block all public access
- Check the acknowledge that the bucket will be public
- Click on create bucket
## Upload files to S3 bucket
- Click on the bucket name
- Click on upload
- Click on add files
- Select the files ( index.html style.css ) and click on upload
- Click on the bucket name
- Click on the file name
- Click on the make public

## Enable static website hosting
- Click on the bucket name
- Click on the properties
- Click on the static website hosting
- Click on the use this bucket to host a website
- Enter the index.html in the index document
- Click on save changes
- Copy the endpoint URL and paste it in the browser

# License
This project is licensed under the MIT License - see the LICENSE.md file for details

# Author
Julie Awonga - julienawon@gmail.com

# Acknowledgements
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteEndpoints.html
