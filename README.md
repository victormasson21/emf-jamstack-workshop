# CI/CD - JAMStack EMF Workshop 🔥

👨🏻‍💻EMF Students. This branch is for serving instructions on the AWS section of the workshop.

Instructions:
  1. Head to the URL on the right and login with your given username and password.

  2. In the menu “Services” select “S3” under Storage. 

  3. These are all the S3 “buckets” currently used. Click Create Bucket.

  4. Enter a bucket name (1 word) and region that the server is hosted at. (usually closest to you). Untick “Block all public access” and tick the agreement. Then click Create bucket

  5. Find your bucket in the list and click it.

  6. Click on Permissions -> Bucket Policy

  7. Grab the code that’s on the link provided and enter it into the Policy editor. Replace <yourbuckethere> with the name of your bucket name. Click save.

  8. Click Properties and then Static website hosting. 

  9. Click Use this bucket to host a website and add index.html into the first field and then click Save.

  10. Test everything is working by uploading a index.html file under Overview, click upload, then click on the file in Overview and go to the URL at the bottom.  	   

💥You should now be ready to integrate AWS with Gatsby Cloud. 👍🏼


## Integrate AWS with Gatsby Cloud
Note: For the next steps will need your S3 
(In AWS, you can find these under the user menu and go to My Security credentials)
- Secret key
- Access key ID

---------
1. Login to your Gatsby Cloud account

2. From the main dashboard, go to site settings.

3. From the left hand menu, select Integrations and then Hosting.

4. Under hosting integrations, find the row that contains AWS and select connect.

5. Enter the first 3 fields and Click save. It should then take you to the previous page and say ‘connected’.

6. Now test out your configuration by going to the production tab and selecting ‘manual build’. It should then repeat the process of building and then underneath once it’s built, say deploying to S3. If successful, it will change to Deployed to S3. Check your AWS url!

Contragtulations! You have now successfully setup CI  with Gatsby Cloud and AWS. 👍🏼
