# Project-AWS-DevOps-Practice-Lab
Hands-on learning journey focused on Linux CLI, Git, EC2, IAM, S3, and foundational DevOps tools.

🗂️ Week-by-Week Progress

✅ Week 1: Git & CLI Basics
✔️ Installed Git and configured username/email
✔️ Learned git init, clone, add, commit, push, pull, log, status
✔️ Practiced branching: git branch, checkout, merge, conflict resolution
✔️ Basic Linux CLI: ls, cd, pwd, touch, mkdir, rm, mv, cp

✅ Week 2: Linux Deep Dive + Permissions
✔️ File permissions (chmod, chown, ls -l)
✔️ Redirection & Pipes: >, >>, |, tee
✔️ Text processing: cat, grep, awk, sed, head, tail
✔️ Bash scripting basics: variables, conditionals, loops

✅ Week 3: AWS IAM & EC2 Setup
✔️ Created EC2 Instance (Amazon Linux 2)
✔️ Connected via SSH using PowerShell & key pair
✔️ Configured IAM roles and attached policies for secure access
✔️ Used scp to transfer files to/from EC2

✅ Week 4: S3 Bucket Integration + AWS CLI
✔️ Installed AWS CLI & configured using Access Keys
✔️ Created S3 bucket via CLI
✔️ Commands practiced:
aws s3 ls
aws s3 cp
aws s3 sync
aws s3 rm
✔️ Transferred files between local ↔ EC2 ↔ S3

✅ Week 5: EC2 Troubleshooting + sudo Fixes
✔️ Resolved EC2 instance not connecting via SSH
✔️ Understood role of ec2-user vs root
✔️ Installed sudo using user data script
✔️ Gained deeper understanding of Linux privilege management

🔐 IAM Policy & Role Practice
Created IAM user with programmatic access
Attached custom IAM policies for S3 and EC2
Assigned IAM role to EC2 instance for temporary access to AWS services (no access key used)

💡 Real-World Learnings
Handling EC2 failures and SSH connection issues
Root vs sudo vs user-level permissions
IAM policy debugging
Secure file transfers (SSH, SCP, S3 CLI)
Commands commonly asked in interviews

📘 What's Next (Coming Weeks)
Deploy static site via S3
Introduction to DevOps: CI/CD, Jenkins, Docker
Monitoring with CloudWatch
Infrastructure as Code (IaC) with Terraform or CloudFormation

🙋‍♂️ Maintained By
Mahesh Ushir – Data Analyst & Automation Strategist
