# Streamlining Ticket Assignment for Efficient Support Operations

This project aims to enhance the operational efficiency of ABC Corporation’s support department by implementing an automated system that routes tickets to the appropriate teams based on issue type and user roles. Built on the ServiceNow platform, the solution utilizes update sets, dictionary customizations, and flow-based automation.

## 🚀 Features

- 🔄 **Automated Ticket Routing** using Flow Designer
- 🔐 **Role-based Access Control (ACLs)** to ensure secure ticket handling
- 📅 **Custom Fields** like Ticket Raised Date and Issue Details
- 🧠 **Dynamic Assignment Logic** based on issue content
- 📊 **Optimized Team Workloads** and reduced resolution time

## 📁 Contents

- `streamlining project.xml`: Contains all update sets, ACLs, dictionary entries, roles, and flow configurations.
- `sys_dictionary_u_operations_related_u_ticket_raised_date`: Custom field for ticket creation timestamp.
- `sys_security_acl_*`: ACL configurations securing field-level and table-level operations.
- `sys_hub_flow_*`: Flow Designer logic for triggering automated assignments.

## 🛠️ Setup Instructions

1. Import the `streamlining project.xml` into your ServiceNow instance via Update Sets.
2. Preview and commit the changes carefully to ensure all configurations are loaded.
3. Assign roles such as `platform_role` to users for role-based access.
4. Test the ticket creation process and verify that tickets are routed appropriately.

## 🧑‍💻 Technologies Used

- ServiceNow Platform (Global Scope)
- Flow Designer
- Update Sets
- Access Control Rules (ACL)
- Role-based Security

## ✅ Benefits

- Reduces manual triaging of support tickets
- Minimizes issue resolution time
- Improves customer satisfaction
- Secures sensitive ticket fields using ACLs
- Enhances visibility and tracking through timestamp fields

## 📬 Contact

For issues, questions, or feature requests, feel free to raise an issue or contact the maintainer.

---

*Streamlining IT support with automation to make service faster, smarter, and more secure.*
