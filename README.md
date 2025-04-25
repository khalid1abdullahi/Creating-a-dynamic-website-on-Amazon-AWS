# Creating-a-dynamic-website-on-Amazon-AWS

## Overview

This lab demonstrates launching and configuring a WordPress website using Amazon AWS EC2. It includes steps from launching the instance to customizing the WordPress site and terminating the instance.

---

## Steps

### 1. Launching the EC2 Instance
- Launched **WordPress Certified by Bitnami and Automattic** from AWS Marketplace.
- Selected a **Free Tier Eligible** instance.
- Enabled **Public IP**, default storage and tags.
- Set **Security Group** to allow traffic from `0.0.0.0/0`.

<img src="https://github.com/user-attachments/assets/a5d67b56-4b62-4105-ad8d-7f56151558fc" height="100%" width="100%"/>

---

### 2. Website Access
- Copied the **Public DNS** and accessed the WordPress site from the browser.

<img src="https://github.com/user-attachments/assets/c3300a27-74a2-4445-b523-00642661b957" height="100%" width="100%"/> 

---

### 3. Customizing the Website
- Modified the "Hello World" post and added name.
- Created a new page/post with student ID.


<img src="https://github.com/user-attachments/assets/b9bc13ce-edc2-489b-a8ed-f703331201be" height="100%" width="100%"/>

<img src="https://github.com/user-attachments/assets/558559b3-4e0c-4969-9cc1-df38dcfdfbb2" height="100%" width="100%"/>

---

### 4. Changing Theme & Terminating Instance
- Applied a new WordPress theme.
- Terminated the EC2 instance from the AWS dashboard.


<img src="https://github.com/user-attachments/assets/70a57a89-fe45-4aaa-8147-b02c02bb0aee" height="100%" width="100%"/> 

---

## Notes

All screenshots are stored in the `screenshots/` folder.  
This lab demonstrates the basic workflow of launching, configuring, and tearing down a web server on AWS EC2.

