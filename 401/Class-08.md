# Read 08

## Access Control (ACL)

### 5 steps to RBAC<sup>1</sup>

#### 1. What is Role Based Access Control (RBAC) and why do we care?

"RBAC is the idea of assigning system access to users based on their role in an organization. It's important to remember that not every employee needs a starring role." RBAC ensures only people with certain permissions can do certain things.

#### 2. Describe a Role/Permission heirarchy that you might implement using RBAC.

The top role has the permissions of that role plus all of the permissions of the preceding roles, down the chain until the bottom role

#### 3. What approach might you take to implement RBAC?

* Group workforce members into roles with common access needs
* Assign people to roles

### wiki - RBAC<sup>2</sup>

#### 1. If Authentication is “you are who you say you are,” what is Authorization?

"This is what you can do"

#### 2. Name three primary rules defined for RBAC.

* Role assignment
* Role authorization
* Permission authorization

#### 3. Describe RBAC to a non-technical friend.

It's like a general office set up - your manager can do some things that you cannot, including the things you can do.  But, your manager cannot do some of the things his boss can do

### RBAC Tutorial<sup>3</sup>

#### 1. What Are access rights Associated with? The User? or The Role? Explain.

Roles. Each user is designated as filling a role, which will then determine their permissions.

#### 2. Access Rights, or Authorization, is activated after a user successfully does what?

Authenticates themselves to the system

#### 3. Explain how RBAC might benefit a business.

You probably don't want everbody to see the payroll, so only payroll managers have permissions to view it.  You don't want project members to access, and potentially change (maliciously or not) aspects of a project that only project managers should be changing.

* Policy dictates role permissions, regardless of employees leaving or being hired

### Footnotes

<sup>1</sup>https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html

<sup>2</sup>https://en.wikipedia.org/wiki/Role-based_access_control

<sup>3</sup>https://www.youtube.com/watch?v=C4NP8Eon3cA

[Back](/reading-notes/401/401-TOC.html)