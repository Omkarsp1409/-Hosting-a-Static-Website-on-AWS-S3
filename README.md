Introduction
This repository contains all resources and documentation for hosting a static website on AWS S3. Amazon S3 offers scalable object storage ideal for public web content. The guide covers straightforward steps for beginners.

Key Features
Cost-effective: Pay only for storage and data transfer.

High availability: Automatic replication across AWS servers.

Scalability: Effortlessly accommodates heavy or fluctuating traffic.

Steps Included
S3 Bucket Creation: Step-by-step instructions for creating a globally unique S3 bucket in the AWS Console.

Permission Settings: Details on object ownership, bucket policies vs ACLs, and when to disable/enable public access for web hosting.

Uploading Website Files: Best practices for uploading HTML, CSS, JS, images, and other web resources to the bucket.

Making Files Public: Guidelines for granting public read permissions using ACLs, ensuring accessibility.

Enabling Static Hosting: Final setup for static website hosting, including index and error document configurations.

Website Endpoint: How to obtain and share the AWS Region-specific public endpoint for the hosted site.

Example Output
Your hosted site becomes accessible via a public URL similar to:

text
http://static-web-host-project.2025.s3-website.eu-north-1.amazonaws.com
Users can visit this address to view the website content and functionality.

Conclusion
By following these steps, you can deploy a robust, scalable, and publicly accessible static website with AWS S3. This project is ideal for demos, portfolio websites, and learning AWS basics.
