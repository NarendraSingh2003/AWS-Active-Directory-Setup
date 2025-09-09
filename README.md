Task 1: AWS IAM Setup (Admin & Standard User Configuration)

This repository documents my completion of Task 1 from the AWS IAM setup assignment. The task involved configuring IAM users and groups securely using AWS best practices.

✅ Objective

To configure AWS Identity and Access Management (IAM) with:
An Admin user with full access
A Standard user with limited access
MFA (Multi-Factor Authentication) enforced
Root account security ensured

🔧 What I Did
🧑‍💼 1. Created Admin IAM User (cloud-admin)

Enabled console login
Set a password
Assigned virtual MFA device
Attached IAMUserChangePassword policy
Created Admins group with AdministratorAccess policy
Added cloud-admin to Admins group (group-based permissions)

🛡️ 2. Secured the Root Account

Enabled MFA for the root user
Ensured no active access keys for root (best practice)

👥 3. Created Standard IAM User (cloud-user)

Enabled console login
Set a password
Assigned virtual MFA device
Attached ReadOnlyAccess policy (limited permissions)

📂 Screenshots

All steps are supported with screenshots:

User creation
Permissions
MFA setup
Group assignments
Root account security

