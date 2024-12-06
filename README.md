# Hosting-Static-website

#Firstly create the bucket in Amazon s3 bucket
#Go to create bucket and give a unique name as i have given (carvilla1) and enable ACLs so the access to the bucket and the objects can be specified.
![alt text](<Screenshot 2024-12-06 142956-1.png>)
#A list of uploaded files in an S3 bucket named carvilla1.
![alt text](<Screenshot 2024-12-05 230804.png>)
#Editing settings for enabling Static Website Hosting in the S3 bucket.
#The hosting type options include:
#Hosting a static website by using index.html as the default page.
#Redirecting requests to another bucket or domain.
#Mention of making content publicly readable to enable access via the website endpoint.
![alt text](<Screenshot 2024-12-05 230936.png>)
#successfully edited static website hosting
![alt text](<Screenshot 2024-12-05 230948.png>)
#Editing Block Public Access settings for the S3 bucket.
#The bucket provides customizable options:
#Block public access for new/existing ACLs or bucket policies.
#AWS recommends enabling "Block All Public Access" but notes compatibility issues with certain applications.
![alt text](<Screenshot 2024-12-05 231010.png>)
#Go to th objects where making the files publicly using ACLS so that user can use over internet
![alt text](<Screenshot 2024-12-05 231036.png>)
#make the public use see the status of the files which should be successfully edited public acces.
![alt text](<Screenshot 2024-12-06 143614.png>)
#Copy the url link which has benn given in the static webiste host edit in properties and paste it to the new website where u can see the website which is accessible over the internet.
![alt text](<Screenshot 2024-12-06 143630.png>)