# aws-static-website
1.CREATE A BUCKET
           Click on "Create bucket" and follow the prompts. Choose a globally unique name for your bucket. 
2.UPLOAD THE FILES INTO S3 BUCKET
                   Upload your HTML, CSS, JS, and any other assets (images, fonts, etc.) to the S3 bucket.
3.MAKE THE ACCESS AS PUBLIC
               Make sure your bucket and files are publicly accessible. In the bucket's permissions settings, add a bucket policy allowing public read access. 
4.ENABLE STSTIC WEBSITE HOSTING 
                Make sure that static website hosting is enabled for your bucket. In the bucket properties, under "Static website hosting", you should see the endpoint URL for your website. It will look something like http://portfolio1-static-website.s3-website-region.amazonaws.com
5.TEST YOUR WEBSITE
             Visit the endpoint URL in your web browser to make sure your website is accessible.
