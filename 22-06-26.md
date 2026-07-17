# Day 1 Training Diary – Introduction to Cloud Computing & AWS

**Date:** 22/06/2026

# Day 1 Summary

Today I learned:

- Fundamentals of Cloud Computing
- Service Models (IaaS, PaaS, SaaS)
- Introduction to AWS
- AWS Account Creation Process
- Common AWS Services
- Basic Linux Commands
- IAM User and Group Management
- Multi-Factor Authentication (MFA)

This session provided a strong foundation for working with cloud technologies and AWS services.



---

# Introduction to Cloud Computing

Cloud computing is the delivery of computing services such as servers, storage, databases, networking, software, and analytics over the internet. Instead of purchasing and maintaining physical hardware, users can rent resources from cloud providers and access them on demand.

## Advantages of Cloud Computing

- Pay-as-you-go pricing
- High scalability
- Global accessibility
- Automatic updates
- Better disaster recovery
- Reduced infrastructure costs

---

# Cloud Service Models

## IaaS (Infrastructure as a Service)

Provides virtual machines, storage, networking, and other infrastructure resources.

**Examples:**
- Amazon EC2
- Microsoft Azure VM
- Google Compute Engine

## PaaS (Platform as a Service)

Provides a platform for developers to build, test, and deploy applications.

**Examples:**
- AWS Elastic Beanstalk
- Google App Engine
- Heroku

## SaaS (Software as a Service)

Provides software applications through the internet.

**Examples:**
- Spotify
- Gmail
- Microsoft 365
- Google Docs

---

# Introduction to AWS

Amazon Web Services (AWS) is Amazon's cloud computing platform that provides more than 200 cloud services across computing, storage, networking, databases, analytics, machine learning, and security.

AWS is one of the most widely used cloud platforms because of its scalability, reliability, global reach, and pay-as-you-go pricing model.

## Benefits of AWS

- Global infrastructure
- High availability
- Enhanced security
- Cost optimization
- Elastic scalability
- Large service ecosystem

## Popular AWS Services

| Service | Purpose |
|----------|----------|
| EC2 | Virtual Servers |
| S3 | Object Storage |
| IAM | Identity and Access Management |
| RDS | Managed Databases |
| VPC | Virtual Private Cloud |
| Lambda | Serverless Computing |
| CloudWatch | Monitoring and Logging |

---

# Steps to Create an AWS Account

1. Open https://aws.amazon.com
2. Click **Create an AWS Account**.
3. Enter email address, account name, and password.
4. Verify your email.
5. Select Personal or Business account.
6. Enter contact information.
7. Add payment information.
8. Verify phone number using OTP.
9. Choose the Basic Support Plan.
10. Sign in to the AWS Management Console.

---

# Linux Commands Learned

Linux is a command-line based operating system widely used in cloud environments and AWS servers.

## Basic Commands

### Current Directory

```bash
pwd
```

Displays the present working directory.

### Current User

```bash
whoami
```

Displays the currently logged-in user.

### List Files

```bash
ls
```

Lists files and directories.

### Detailed File List

```bash
ls -l
```

Shows permissions, owner, size, and modification date.

### Sort by Latest Modified Time

```bash
ls -lt
```

Lists files sorted by latest modification.

### Show Hidden Files

```bash
ls -a
```

Displays hidden files and directories.

### Display Current Date

```bash
date
```

Shows the current system date and time.

### Display Date Format

```bash
date +%D
```

Shows date in MM/DD/YY format.

### Change Directory

```bash
cd folder_name
```

Moves into a directory.

### Move Back One Directory

```bash
cd ..
```

Moves to the parent directory.

### Create Directory

```bash
mkdir myfolder
```

Creates a new directory.

### Remove Empty Directory

```bash
rmdir myfolder
```

Deletes an empty directory.

### Create File

```bash
touch file.txt
```

Creates an empty file.

### View File Content

```bash
cat file.txt
```

Displays file contents.

### Copy File

```bash
cp file1.txt file2.txt
```

Copies a file.

### Rename/Move File

```bash
mv old.txt new.txt
```

Renames or moves a file.

### Delete File

```bash
rm file.txt
```

Removes a file.

### Clear Terminal

```bash
clear
```

Clears the terminal screen.

### Display Command Manual

```bash
man ls
```

Displays the manual page for a command.

---

# IAM (Identity and Access Management)

IAM is an AWS service used to manage users, groups, roles, and permissions securely.

## Features

- User Management
- Group Management
- Role-Based Access Control
- Permission Policies
- MFA Support

## MFA (Multi-Factor Authentication)

MFA adds an additional security layer by requiring users to verify their identity using a second authentication method such as:

- Authenticator App
- SMS OTP
- Hardware Security Key

### Benefits of MFA

- Improved account security
- Protection against password theft
- Reduced unauthorized access

---
