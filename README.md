
# AWS Static Website Project

This repository contains a simple static website that was hosted on **Amazon S3** as part of my AWS DevOps learning journey.  

## Project Overview
- Built using **HTML** (`index.html` as the main entry point).
- Deployed to **AWS S3 bucket** for static hosting.
- Practiced version control with **Git & GitHub**.
- Documented AWS bucket policy for learning IAM and S3 security.

## Folder Structure

- `aws-devops-class/` → Coursework folder containing project files and supporting assets  
  - `index.html` → Website file used in class exercises  
  - `policy.txt` → AWS bucket policy reference (kept here as part of the class project structure)  
  - `Screenshot w.png` → Screenshot of the deployed static website (kept here for coursework completeness)  

- `index.html` → Main static website file (root level for GitHub Pages hosting)  
- `README.md` → Project overview and documentation  
- `policy.txt` → AWS bucket policy reference (root level for quick access)  
- `Screenshot w.png` → Screenshot of the deployed static website (root level for quick access)  

> Note: The bucket policy reference (`policy.txt`) and screenshot are intentionally included both at the repo root for quick access and inside the `aws-devops-class` folder as part of the coursework structure.

## Learning Goals
- Understand how to host static websites on AWS S3.
- Practice Git basics (`init`, `add`, `commit`, `push`).
- Use GitHub as a backup and portfolio reference.
- Document infrastructure configuration alongside code.

---

## AWS Bucket Policy Reference

This project includes a `policy.txt` file that contains the **Amazon S3 bucket policy** used to configure access permissions for hosting the static website.  

- The policy grants public read access to objects in the bucket.  
- It serves as a reference for learning AWS IAM and S3 security configurations.  
- You can reuse or adapt this policy when setting up similar static website hosting projects.  

> Always review and adjust bucket policies carefully to avoid exposing sensitive data.

---

## Screenshots

Below is a screenshot of the static website successfully hosted on **Amazon S3**:

![AWS Static Website Screenshot](Screenshot%20w.png)

> The screenshot shows the deployed `index.html` page, confirming that the site was publicly accessible via the S3 bucket configuration.
