Background1

A security incident refers to any event or occurrence that compromises the confidentiality, integrity, or
availability of an organization's information systems, data, or resources. Security incidents can take
various forms and may result from intentional attacks, accidental actions, or natural disasters. Examples
of security incidents include:
• Unauthorized access: Attempts to gain unauthorized access to sensitive systems, applications, or
data, often through exploitation of vulnerabilities or weak authentication mechanisms.
• Data breaches: Unauthorized disclosure or exposure of sensitive or confidential information, such
as personal data, financial records, or intellectual property, to unauthorized parties.
• Malware infections: Infections caused by malicious software (malware), including viruses, worms,
Trojans, ransomware, and spyware, which can disrupt operations, steal data, or cause other
harmful effects.
• Denial-of-service (DoS) attacks: Attempts to disrupt or degrade the availability of services,
applications, or networks by overwhelming them with a flood of traffic or malicious requests.
• Insider threats: Breaches or incidents caused by authorized users or employees who misuse their
privileges, intentionally or unintentionally, to compromise security or harm the organization.
• Social engineering attacks: Manipulative tactics used to deceive or manipulate individuals into
divulging sensitive information, such as passwords, credentials, or financial details.
• Physical security breaches: Incidents involving unauthorized access to physical premises, theft of
hardware or storage media, or destruction of equipment or facilities.
• Compliance violations: Instances where organizations fail to comply with legal, regulatory, or
industry-specific requirements related to data protection, privacy, or security.
Security incidents pose significant risks to organizations, including financial losses, reputational
damage, legal liabilities, and disruptions to operations. Effective incident detection, response, and
mitigation strategies are essential for minimizing the impact of security incidents and safeguarding
organizational assets and stakeholder



Project Description
The goal of this project is to develop an Incident Response Portal, which is a web-based platform
designed to streamline and manage the process of incident response within an organization. The portal
serves as a centralized hub for reporting, tracking, and resolving security incidents, enabling timely
response and mitigation efforts by security teams and incident responders.
Project Features (Requirements)
1. User Authentication and Authorization
a. The portal supports user authentication, allowing registered users to log in and logout
using their credentials.
b. User roles and permissions are enforced to ensure that users have appropriate access
levels based on their responsibilities.
c. User roles are: “incident reporters”, “incident responders”, and “administrators”. Each have
distinct sets of permissions and access rights.
2. User Management
a. Administrators have access to a dedicated user management interface within the portal.
b. Using the user management interface, administrators can register new users directly within
the system.
c. When registering new users, administrators input necessary user information, including
username, email address, password, and user role.
d. Administrators can assign specific roles (see 1.c) and permissions to newly registered users,
customize user attributes, and manage user accounts effectively. More specifically:
i. Incident reporters: report incidents and see their reported incidents and their
statuses. Can add comments and evidence to their reported incidents.
ii. Incident responders: report incidents and see all reported incidents and their
statuses. Can add comments and evidence to all reported incidents. Can change
the status of a reported incident.
iii. Administrators: report incidents and see all reported incidents and their statuses.
Can add comments and evidence to all reported incidents. Can change the status
of a reported incident. Can manage users and see web site statistics.
3. Incident Reporting
a. Users can report security incidents through the portal by filling out a structured incident
report form.
b. The form collects essential information such as incident type2, severity3, description,
affected assets, and timestamps.
c. Users must have the option to attach relevant files or evidence to their incident reports for
further analysis.



4. Incident Tracking and Management
a. Reported incidents are logged into a centralized database and assigned unique identifiers
for tracking purposes.
b. Users can view the status of reported incidents, including pending, in progress, and
resolved incidents.
c. Incident responders can update incident status4, add comments, and collaborate on
incident resolution efforts within the portal.
5. Incident Analytics and Reporting
a. The portal includes built-in analytics and reporting features to generate insights into
incident trends, patterns, and metrics.
b. Users can view reports (tabular format) and visualizations (graphs) to analyze incident data
over time, identify recurring threats, and assess the effectiveness of incident response
strategies.
6. Page Visit Tracking
a. The portal will track and record page visits to analyze user behavior and improve user
experience.
b. Each time a user visits a page, the visit will be logged in the database along with the user's
ID (if logged in), host IP, host web browser, and the timestamp of the visit.
c. Administrators can view:
i. Full visit log reports (tabular format),
ii. Visit log reports (tabular format) per user,
iii. Summary of page visits by page.
7. The following users, and respective credentials, must exist in the system:
a. System Administrator:
• User Name: administrator
• Password: administrator
b. Incident Reporter:
• User Name: reporter
• Password: reporter
c. Incident Responder:
• User Name: responder
• Password: responder
8. Students are more than welcome to add more features to the system!
