# Determining Permissive Structure:

# SUMMARY:
   - Issue: Determining the permissions management approach for the retail company's web app.
   - Decision: Opting for Role-Based Access Control (RBAC) for its simplicity, scalability, and flexibility.
   - Status: Decision made, proceeding with RBAC for permissions management.

# DETAILS
   -Assumptions:
     	- Assuming the need for granular control over user access to app features and data.
   -Constraints:
     	- Consideration of scalability and ease of maintenance as the user base grows.
   -Position:
     	- Advocating for RBAC due to its well-defined roles, permissions, and ease of implementation.
   -Arguments:
     	- RBAC simplifies access control by assigning roles to users and granting permissions based on those roles, reducing complexity and improving security.
   -Implications:
     	- Streamlined management of user access rights through role assignments and permissions.
     	- Potential need for periodic review and adjustment of roles and permissions to align with changing business requirements.

# RELATED
   -  Related Decisions:
     	- Adoption of RBAC aligns with the decision to prioritise simplicity and scalability in permissions management.
   - Related Requirements:
     	- Ensuring flexibility to define roles and permissions based on the needs of different user groups within the app.

# NOTES
   - Regular auditing of user roles and permissions is essential to maintain the integrity and security of the app.
