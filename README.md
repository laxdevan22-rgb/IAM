## EX - 6 Implementation Of Identity Management (Amazon Iam) For Your Team.
## Aim
## NAME : V.Lakshita Rai
## REGNO : 212225220054
To implement Identity and Access Management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.


## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.



## Procedure

### 1. Access IAM
- Go to **AWS Console** → **Services** → **IAM**

### 2. Create IAM Groups
- Click **Groups** → **Create New Group**
- Name the group (e.g., `Admins`, `Developers`)
- Attach predefined or custom policies (e.g., `AmazonEC2FullAccess`, `ReadOnlyAccess`)

### 3. Create IAM Users
- Click **Users** → **Add Users**
- Provide usernames
- Choose access type:
  - **Programmatic access**
  - **AWS Management Console access**
- Assign users to the appropriate IAM group

### 4. Create IAM Roles (Optional)
- Go to **Roles** → **Create Role**
- Select a use case:
  - AWS service
  - Another AWS account
- Attach policies as required

### 5. Apply Policies
- Use AWS Managed Policies or create custom policies using JSON
- Attach them to:
  - Users
  - Groups
  - Roles

### 6. Enable Multi-Factor Authentication (MFA)
- Go to the IAM user → **Security credentials**
- Click **Manage MFA**
- Choose **Virtual MFA device** (e.g., Google Authenticator)

### 7. Monitor IAM Usage
- Use **IAM Access Analyzer** to review access
- Use **AWS CloudTrail** to audit actions and access logs


## Scenario
<img width="503" height="172" alt="Screenshot 2025-11-15 at 11 03 27 AM" src="https://github.com/user-attachments/assets/dccf8d4c-4a2d-4892-901a-b1f869a89bef" />





## Output
<img width="793" height="407" alt="Screenshot 2026-09-12 143656" src="https://github.com/user-attachments/assets/8793bac2-19a0-420a-bf17-6d3180535cda" />


<img width="792" height="400" alt="Screenshot 2026-09-12 143715" src="https://github.com/user-attachments/assets/bf39f384-ddfc-4b47-8c55-c88400efebf7" />






## Result

Successfully implemented identity and access management using **Amazon IAM**, enabling secure, role-based access control and ensuring team collaboration with best security practices.
