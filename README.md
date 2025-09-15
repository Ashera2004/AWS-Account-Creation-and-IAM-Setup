# EX NO. 1: AWS-Account-Creation-and-IAM-Setup

**NAME:** A S Siddarth  
**REG NO:** 212224040316  

---

## Aim
To create an AWS account, set up a root user, and create an IAM user with administrative access.  

---

## Procedure

### Step 1: Create an AWS Account
- Go to [AWS Website](https://aws.amazon.com).  
- Click **“Create an AWS Account”** on the top right corner.  
- Provide the following details:  
  - **Email address:** Use a valid email ID.  
  - **Password:** Choose a strong password.  
  - **AWS Account Name:** Enter your name or organization name.  
- Select account type (**Personal/Professional**) and enter contact details.  
- Provide **credit/debit card details** (required for account verification).  
- Verify your identity using your phone number (via **OTP call or SMS**).  
- Choose the **Basic Support Plan (Free)** for beginners.  
- Click **“Sign Up”** and wait for the confirmation email.  

---

### Step 2: Sign in as the Root User
- Go to **AWS Console**.  
- Choose **Root user** and enter your AWS account email and password.  
- After logging in, **secure the root user account** by enabling **Multi-Factor Authentication (MFA)**.  

---

### Step 3: Enable IAM Identity Center (Optional for Organizations)
- Navigate to **IAM Identity Center** in the AWS Console.  
- Enable it to manage users and assign permissions more securely.  

---

### Step 4: Create an IAM User
- Open the **IAM (Identity and Access Management)** service from the AWS Console.  
- Click **Users → Add Users**.  
- Enter a username (e.g., `admin-user`).  
- Select **Programmatic access** and **AWS Management Console access**.  
- Set a password for console access.  
- Assign **AdministratorAccess** policy to this IAM user.  
- Review and create the user.  
- Download the **.csv file** containing the IAM user’s login credentials.  

---

### Step 5: Sign in as the IAM User
- Use the **sign-in URL** provided in the IAM dashboard.  
- Log in with the **IAM username and password**.  
- From now on, use this IAM user for daily tasks **instead of the root user**.  

---


## Output

<img width="1920" height="1200" alt="Screenshot 2025-09-15 134828" src="https://github.com/user-attachments/assets/698a38c8-e4e6-498e-b537-f00b4536e6be" />


<img width="1920" height="1200" alt="Screenshot 2025-09-15 134901" src="https://github.com/user-attachments/assets/d8a4f72a-98b1-4164-953e-3ab5782de96b" />

<img width="1920" height="1200" alt="Screenshot 2025-09-15 134941" src="https://github.com/user-attachments/assets/32ec0390-2e40-48d7-b0eb-d90cd2d048a8" />
