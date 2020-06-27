# Overview

![security-img](../static/images/icons_human_security.png)

The *human security* knowledge area focuses on protecting individuals’ data and privacy in the context of organizations (i.e., as employees) and their personal lives, in addition to the study of human behavior as it relates to cybersecurity.

## Role-Based Access Control Matrix

Role-Based Access Control (RBAC) matrices, as a security architecture concept, area way of representing access control strategies visually. They help the practitioner ensure that the access control strategy aligns with the specific access control objectives. Matrices also help show when access controls may conflict with job roles and responsibilities.

When designing an RBAC matrix there are few questions to think about and objectives to achieve.

- Ensure individuals have access to necessary information for their job role
- Maintain the Fundamental Security Design Principle of least privilege
- Who should not have permission?

Examples:

| Users | Job Role | Job Duties |
|-------|----------|------------|
| Alice | Human Resources | Access and modify personnel records |
| Bob   | IT Help Desk | Reset Passwords<br>Unlock accounts |
| Craig | CEO | Makes business plans, policy, and strategy |
| Eve   | Auditor | Review files, logs, and security practices |

| User | Customer Information | Employee Information | Backups | User Accounts | Intranet |
|------|:--------------------:|:--------------------:|:-------:|:-------------:|:--------:|
| Alice | None                | View Modify Delete   | None    | None          | View     |
| Bob   | None                | None                 | Create  | View Modify   | View     |
| Craig | View                | None                 | None    | None          | Modify View |
| Eve   | None                | None                 | View    | View          | View     |
