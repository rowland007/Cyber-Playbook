!!! warning

    This page is under construction. There is the possibility that the information below is false or incomplete.

## Common Definitions

!!! abstract "Comparing Permissions, Rights, and Privileges"

    === "Permissions"

        In general, permissions refer to the access granted for an object and determine what you can do with it. If you have *read* permission for a file ...

    === "Rights"

        A right primarily refers to the ability to take an action ...

    === "Privileges"

        *Privileges* are the combination of rights and permissions. For example, an ...

!!! abstract "Authorization Mechanisms"

    === "Implicit Deny"

        A basic principle of access control is *implicit deny* and most authorization mechanisms use it.

    === "Access Control Matrix"

        An *access control matrix* is a table that includes subjects, objects, and assigned privileges.

    === "Capability Tables"

        *Capability tables* are another way to identify privileges assigned to subjects.

    === "Content-Dependent Control"

        *Content-dependent access controls* restrict access to data based on the content within an object.

    === "Context-Dependet Control"

        *Context-dependent access controls* require specific activity before granting users access.

    === "Need to Know"

        This principle ensures that subjects are granted access only to what they *need to know* for their work tasks and job functions.

    === "Least Privilege"

        The *principle of least privilege* ensures that subjects are granted only the privileges they need to perform their work tasks and job functions.

    === "Separation of Duties and Responsibilities"

        System of checks and balances.

## Discretionary Access Control

!!! info

    SharePoint is an example of Discretionary Access Control (DAC).

## Role-Based Access Control

!!! info

    User groups are an example of Role-Based Access Control (RBAC). e.g. SharePoint Administrator, Administrator, user, etc.

Role-Based Access Control (RBAC) matrices, as a security architecture concept, area way of representing access control strategies visually. They help the practitioner ensure that the access control strategy aligns with the specific access control objectives. Matrices also help show when access controls may conflict with job roles and responsibilities.

When designing an RBAC matrix there are few questions to think about and objectives to achieve.

- Ensure individuals have access to necessary information for their job role
- Maintain the Fundamental Security Design Principle of least privilege
- Who should not have permission?

???+ example "Access Control Matrix Examples"

    === "Example 1"

        | Users | Job Role | Job Duties |
        |-------|----------|------------|
        | Alice | Human Resources | Access and modify personnel records |
        | Bob   | IT Help Desk | Reset Passwords<br>Unlock accounts |
        | Craig | CEO | Makes business plans, policy, and strategy |
        | Eve   | Auditor | Review files, logs, and security practices |

    === "Example 2"

        | User | Customer Information | Employee Information | Backups | User Accounts | Intranet |
        |------|:--------------------:|:--------------------:|:-------:|:-------------:|:--------:|
        | Alice | None                | View Modify Delete   | None    | None          | View     |
        | Bob   | None                | None                 | Create  | View Modify   | View     |
        | Craig | View                | None                 | None    | None          | Modify View |
        | Eve   | None                | None                 | View    | View          | View     |

## Rule-Based Access Control

!!! info

    Access Control Lists (ACLs) within firewalls are an example of Rule-Based Access Control.

## Attribute Based Access Control

!!! info

    Locking down remote access to a specific IP is an example of Attribute Based Access Control (ABAC). Usually, an *if* this "attribute" is *true* then grant access otherwise deny.

## Mandatory Access Control

!!! info

    Military classifications like, *CONFIDENTIAL*, *SECRET*, and *TOP SECRET* are examples of Mandatory Access Control (MAC).