# Microsoft Entra ID Access Reviews – Identity Governance Lab

## 📌 Project Overview

This project demonstrates the configuration and use of **Access Reviews in Microsoft Entra ID** to periodically review security group membership, validate users' access requirements, and support the principle of least privilege.

The lab focuses on Identity Governance and how organizations can ensure that users retain only the access they still require.

## 🎯 Objectives

- Configure Microsoft Entra ID Access Reviews.
- Create and manage a security group.
- Assign reviewers.
- Configure review scope and schedule.
- Evaluate access recommendations.
- Review and make access decisions.
- Understand how access reviews support least privilege.

## 🛠️ Technologies Used

- Microsoft Entra ID
- Identity Governance
- Access Reviews
- Security Groups
- Microsoft Azure Portal

## ⚙️ Lab Implementation

### 1. Security Group Creation
Created a security group named `AZ500Admins` to represent a group whose membership requires periodic validation.

### 2. Group Membership
Added test users to the security group to simulate members requiring access review.

### 3. Access Review Configuration
Created an access review named `AZ500Review` with the following configuration:

- **Review scope:** Selected group
- **Group:** AZ500Admins
- **Reviewers:** Assigned reviewer
- **Schedule:** One-time review
- **Duration:** 7 days

### 4. Review Settings

Configured review settings including:

- Auto-apply results: Disabled
- Non-response action: No change
- Decision helper: Users who have not signed in within 30 days
- Justification required
- Email notifications enabled
- Reminders enabled

### 5. Review and Evaluation

Evaluated the group members and recommendations to determine whether access should be retained or removed.

### 6. Access Decisions

Reviewed the recommendations and considered whether each user still required membership in the group based on access requirements and activity.

### 7. Applying Review Results

The review process demonstrates how access review decisions can be applied to update group membership and remove access that is no longer required.

## 🔐 Security Concepts Demonstrated

- Identity Governance
- Access Reviews
- Access Validation
- Least Privilege
- Security Group Management
- Access Lifecycle Management
- Privileged Access Governance

## 📸 Screenshots / Demo

Screenshots and a demonstration video documenting the lab configuration and workflow can be added here.

## 💡 Key Learning

Access Reviews provide organizations with a structured way to periodically validate user access. They help identify unnecessary permissions, improve accountability, and reduce the risk of excessive access remaining in place indefinitely.

## 🚀 Conclusion

This hands-on lab strengthened my practical understanding of Microsoft Entra ID Identity Governance and Access Reviews, particularly how periodic access validation supports security, accountability, and the principle of least privilege.

---

**Author:** Oni Victor Kehinde  
**Focus:** IAM | Cloud Security | Identity Governance
