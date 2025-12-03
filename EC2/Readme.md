
PS C:\Users\rajha\Downloads> ssh -i "yash_key.pem" ec2-user@ec2-13-61-190-206.eu-north-1.compute.amazonaws.com
   ,     #_
   ~\_  ####_        Amazon Linux 2023
  ~~  \_#####\
  ~~     \###|
  ~~       \#/ ___   https://aws.amazon.com/linux/amazon-linux-2023
   ~~       V~' '->
    ~~~         /
      ~~._.   _/
         _/ _/
       _/m/'
Last login: Wed Dec  3 12:36:04 2025 from 103.157.169.68
[ec2-user@ip-172-31-30-206 ~]$ sudo yum update -y
Last metadata expiration check: 0:15:16 ago on Wed Dec  3 12:37:29 2025.
Dependencies resolved.
Nothing to do.
Complete!
[ec2-user@ip-172-31-30-206 ~]$ sudo dnf update -y
Last metadata expiration check: 0:15:53 ago on Wed Dec  3 12:37:29 2025.
Dependencies resolved.
Nothing to do.
Complete!
[ec2-user@ip-172-31-30-206 ~]$ sudo dnf install nginx -y
Last metadata expiration check: 0:16:16 ago on Wed Dec  3 12:37:29 2025.
Package nginx-1:1.28.0-1.amzn2023.0.2.x86_64 is already installed.
Dependencies resolved.
Nothing to do.
Complete!
[ec2-user@ip-172-31-30-206 ~]$ sudo systemctl start nginx
sudo systemctl enable nginx
[ec2-user@ip-172-31-30-206 ~]$ sudo systemctl enable nginx
[ec2-user@ip-172-31-30-206 ~]$ ^C
[ec2-user@ip-172-31-30-206 ~]$ ^C
[ec2-user@ip-172-31-30-206 ~]$ sudo nano /usr/share/nginx/html/index.html
[ec2-user@ip-172-31-30-206 ~]$ systemctl restart nginx
Failed to restart nginx.service: Access denied
See system logs and 'systemctl status nginx.service' for details.
[ec2-user@ip-172-31-30-206 ~]$ sudo nano index.html
[ec2-user@ip-172-31-30-206 ~]$ sudo systemctl restart nginx
[ec2-user@ip-172-31-30-206 ~]$ 
convert this in a readme file 
