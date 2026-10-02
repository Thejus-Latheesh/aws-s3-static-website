# Host a Static Website on Amazon S3

## Overview
A multi-page portfolio website hosted on Amazon S3 using static website hosting.

## Architecture
User → S3 Bucket → index.html → Website

## AWS Services Used
- Amazon S3
- S3 Static Website Hosting
- S3 Bucket Policy

## Steps I Followed
1. Created an S3 bucket
2. Uploaded the HTML and CSS files
3. Enabled static website hosting
4. Configured Block Public Access and a bucket policy for public read
5. Tested the website endpoint

## What I Learned
- How S3 serves static content
- How bucket policies control access
- Why AWS recommends CloudFront for secure hosting
