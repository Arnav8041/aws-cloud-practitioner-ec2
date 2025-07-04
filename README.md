# AWS EC2 Mini-Project 🚀

Welcome to my first **AWS Cloud Practitioner mini-project**! I launched an **Amazon EC2 instance**, attached an **IAM role**, ran a **User Data script** to create a file, and verified details using **AWS CLI** in CloudShell. This project deepened my understanding of **AWS security** and the **Shared Responsibility Model**.

## Project Overview

- **Objective:** Launch an EC2 instance with an IAM role, execute a User Data script, and verify metadata via AWS CLI.
- **Skills Gained:** EC2, IAM, AWS CLI, CloudShell, User Data scripts.
- **Why It Matters:** Demonstrates secure cloud setup, critical for roles like Cloud Support Associate.

## Key Files

- **script.sh:** User Data script to create a file on the instance:
    ```
    #!/bin/bash
    echo "Hello, AWS!" > /home/ec2-user/testfile.txt
    ```
- **screenshots/**: 8 images of the process (IAM setup, EC2 launch, CLI outputs).

## CLI Commands Used

- `aws sts get-caller-identity`
- `curl http://169.254.169.254/latest/meta-data/`

## Screenshots

See the `screenshots/` folder for visuals of the process, including:
- IAM role creation
- EC2 instance launch
- User Data script input
- CLI and metadata outputs

[Full project write-up on Dev.to]([Insert Dev.to link]) for detailed steps and reflections.

## Lessons Learned

- Mastered secure IAM role configuration and EC2 setup.
- Improved troubleshooting skills by debugging script errors.
- Understood AWS’s Shared Responsibility Model for cloud security.

## What's Next?

I’m exploring **S3** and **Lambda** for my next mini-projects. Suggestions? Connect with me on [LinkedIn]([Insert LinkedIn URL]) or [X]([Insert X URL])! #AWS #LearnInPublic

---

*Built as part of my AWS Cloud Practitioner journey, July 2025.*

_Current date: Saturday, July 05, 2025, 3:13 AM IST_
