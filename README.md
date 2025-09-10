# AWS S3 Image Hosting & Static Website

This project guides you through hosting images and deploying a static website using AWS S3. You'll learn to create an S3 bucket, upload and share images, set public access policies, and enable static website hosting with an index.html file for global reach[attached_file:1][web:11][web:24].

## 🚀 Features

- Public image storage on AWS S3
- Static website hosting with custom index.html
- Step-by-step AWS bucket and permissions setup

## 🛠️ Setup Steps

1. **Create S3 Bucket**: Open S3 in AWS Console and create a new, globally unique bucket.
2. **Upload Images/Files**: Add your files and images to the bucket.
3. **Configure Access**: Unblock public access in bucket settings and add a public read bucket policy.
4. **Enable Static Website Hosting**: Set index.html as the website's entry point in the bucket properties.
5. **Access Website**: Use the generated S3 website endpoint to view your site.

## 📦 Example Bucket Policy

```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::YOUR_BUCKET_NAME/*"
    }
  ]
}
```
Replace `YOUR_BUCKET_NAME` with your actual bucket name.

## 🔗 Socials

[![GitHub](https://readmecodegen.vercel.app/api/social-icon?name=github&size=40)](https://github.com/yourgithubusername)
[![LinkedIn](https://readmecodegen.vercel.app/api/social-icon?name=linkedin&size=40)](https://www.linkedin.com/in/ateeb-ahmed-shaikh-932234192/)

## 📋 License

MIT or your preferred license.

---

*Inspired by AWS documentation and community guides for simple cloud hosting*[attached_file:1][web:11][web:24].
```
