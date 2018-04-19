2 Security-Enhanced Linux and audit2allow
2.1 Security-Enhanced Linux
2.1.1 What Problems Does SELinux Solve
2.1.2 SELinux Components
2.2 Basic Concepts
2.2.1 Subjects and Objects
2.2.2 Mandatory Access Control
2.2.3 SELinux Users
2.2.4 Role-Based Access Control
2.2.5 Type Enforcement
2.2.6 Multi-Level and Multi-Category Security
2.2.7 SELinux Security Context
2.2.8 Object Classes
2.2.9 Labeling Subjects and Objects
2.2.10 Type Transitions
2.2.11 SELinux Modes of Operation
2.3 SELinux Policy
2.3.1 User, Role and Type Statements
2.3.2 Access Vector Rules
2.3.3 Extended Permission Access Vector Rules
2.3.4 Policy Modules
2.3.5 Conditional Policy
2.3.6 Labeling Network Objects
2.3.7 Interfaces
2.4 File Contexts
2.4.1 Temporary Changes
2.4.2 Type Transition
2.4.3 File Context Configuration Files
2.4.4 Changing File Context Files
2.5 Auditing Security Events
2.5.1 Audit and SELinux
2.6 Troubleshooting SELinux
2.7 The audit2allow Utility
2.7.1 Purpose of audit2allow
2.7.2 Basic Mode of Operation
2.7.3 Command-Line Options
2.7.4 How Does audit2allow Work
2.7.5 Implementation of audit2allow
3 Analysis
3.1 Extended Permission Access Vector Rules
3.1.1 AVC Denials Caused by Extended Permission AV Rules
3.1.2 Generating Extended Permission AV Rules in audit2allow
3.2 Mislabeled Files
3.2.1 AVC Denial Messages Caused by Mislabeled Files
3.2.2 Solving Problems With Mislabeled Files
3.2.3 Improving audit2allow
3.3 Labeling Network Ports, Nodes, and Interfaces
3.3.1 Network Ports
3.3.2 Network Nodes
3.3.3 Network Interfaces
4 Implementation
4.1 Extended Permissions
4.1.1 Parsing AVC Denial Messages
4.1.2 Storing Extended Permissions in Access Vector Sets
4.1.3 Representation of Extended Permission AV Rules
4.1.4 Generating Extended Permission AV rules
4.2 Mislabeled Files
4.2.1 Parsing Path
4.2.2 Checking Default Context
5 Functional Testing
5.1 Unit Tests of Extended Permissions
5.1.1 Testing audit Module
5.1.2 Testing access Module
5.1.3 Testing policygen Module
5.1.4 Testing refpolicy Module
5.2 Integration Tests of Extended Permissions
5.3 Unit Tests of Mislabeled Files
5.3.1 Testing audit Module
5.3.2 Testing policygen Module
6 Conclusion
