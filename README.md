# AWS Static Website Hosting using S3 + CloudFront

This project demonstrates hosting a static website on Amazon S3 and distributing it globally using CloudFront (CDN) with HTTPS enabled and automatic HTTP → HTTPS redirection.

## Live Website
https://myawsproject-site.s3-website.ap-south-1.amazonaws.com/

## AWS Services Used
- Amazon S3 (Static Website Hosting)
- Amazon CloudFront (Content Delivery Network)
- Bucket Policies (Public Read)
- CloudFront Behaviors (Redirect HTTP to HTTPS)

## Steps implemented
1. Created S3 bucket
2. Enabled static website hosting
3. Configured bucket policy for public read
4. Uploaded index.html
5. Created CloudFront distribution
6. Set viewer protocol policy to Redirect HTTP to HTTPS
7. Verified deployment

## How to run
Just open the URL in any browser:
`https://myawsproject-site.s3-website.ap-south-1.amazonaws.com/`

---
