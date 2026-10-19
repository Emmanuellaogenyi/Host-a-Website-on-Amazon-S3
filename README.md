# Host a Website on Amazon S3


**Author:** Emmanuella Ogenyi  
**Email:** emmanuella.ogenyi@gmail.com

---

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_5d4474f9)

## Introducing Today's Project!

### Project overview

### Tools and concepts

Amazon S3 (Simple Storage Services) is an object storage servIce that offers scalability , data availability, security and performance.
it is useful to store and retrieve any amount of data at any time,from anywhere

### Time, challenges, and wins

i used Amazon S3 to host a static website

## How I Set Up an S3 Bucket

### What I did in this step

### How long it took to create the bucket

Creating an S3 bucket took me 5-10 minutes to setup

### Region selection

The region i picked for my S3 bucket was Africa (cape Town) because its the closest to Africa (nigeria)

### Understanding bucket name uniqueness

S3 bucket names are globally unique! this means that you can only use an S3 bucket name once, except the previous bucket was deleted

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_ba6d42ad)

## Upload Website Files to S3

### What I did in this step

### Files I uploaded

I uploaded two files to my S3 bucket—they were index.html. file and Everyone should be in a job they love_files folder

### How the files work together

Both files are necessary for this project, as one contains the HTML files and the second contains the image folder, which work hand in hand to run a website smoothly.

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_a265af88)

## Static Website Hosting on S3

### What I did in this step

### Understanding website hosting

Website hosting is storing an HTML file on a web server, so it is accessible to the public

### How I enabled website hosting

To enable website hosting with my S3 bucket, I went to the properties tab, scrolled to find the static website hosting, choose the hosting type of a static website, entered index.html, then clicked on save changes.

### Access Control Lists (ACLs)

ACL is a set of rules that determine who gets access to a resource/information. I enabled ACLs to give the S3 bucket access to the public

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_c22c54c0)

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is just like a regular website URL, that lets people visit the S3 bucket as a website

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw the reason for this error was that the objects were not made public using the ACL

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_22ce4daf)

## Success!

### What I did in this step

### How I resolved the 403 error

To resolve the connection error, I selected the two objects, clicked on the actions tab and made them public using ACL

![Image](https://nextwork.ai/lively_yellow_swift_lemon_balm/uploads/aws-host-a-website-on-s3_5d4474f9)

## Bucket Policies

### What I did in this extension

### Understanding bucket policies

### What my bucket policy does

---


