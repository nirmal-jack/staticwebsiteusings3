# staticwebsiteusings3
- go to the aws console and create a bucket

  
  ![s3](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/40b58c93-1133-457c-97d2-33850526e5a0)
- There are few things we need to update, under Properties, scroll all the way down and choose static website hosting. choose edit.

  
  ![static](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/335d423c-24cb-42ac-95fb-ecdb3f3e0494)
  - choose enable and give the file name as index.html and save changes.
 
    ![static](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/0218733e-644e-459b-8eec-7742ee0dbf17)

    -After that , the end point for the website will appear at the bottom of the properties page, click on the end point. it will throw an error.
    ![static](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/f00e7ac8-54f8-4e1a-84cf-4acd2e2bb328)



![error](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/907c01f0-f089-4b38-8d6c-193ed6db4910)

- This is because, all public access to the bucket are disabled by default. we have to manually enable it. Go to permissions tab, and enable the public access and save changes.
  ![permissions](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/cc6e25bb-f9cf-47ae-b8a3-b68a77c448e6)


  ![static2](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/7b387ba0-fc79-4678-ba5b-f8fc2a45bfd9)

  - go to bucket policy and edit it under the "Permissions" tab. paste the bucket policy with the bucket name and click on save changes
 

    ![Capture](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/8a04d004-7b3a-4d40-bbd8-f051a7451ec7)

    - go to the s3 bucket and upload the html file and other files as needed.
   
    ![s3](https://github.com/nirmal-jack/staticwebsiteusings3/assets/170439621/7fd35906-35a8-43db-9da5-30afd1ba584c)





  


