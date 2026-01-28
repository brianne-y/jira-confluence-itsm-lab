# Modernizing IT Support: A Self-Service First Approach using Jira & Confluence

## Objective
This project involved the end-to-end implementation of an IT Service Management (ITSM) ecosystem. The core focus was to implement a 'Shift-Left' strategy by integrating Jira Service Management with a Confluence Knowledge Base. I developed a system designed to prioritize user self-service and maximize ticket deflection, reducing the volume of low-complexity issues reaching the agent’s queue and allowing for faster resolution of high-priority incidents.

---

## Project Competencies
* **ITSM Lifecycle Management:** Executed the full lifecycle of an incident, from portal intake and triage to final resolution and closure.
* **Shift-Left Support Strategy:** Implemented a proactive support model by making technical solutions available at the point of request.
* **Knowledge-Centered Service (KCS):** Authored professional, image-rich technical documentation to serve as a "Single Source of Truth."
* **Automated Ticket Deflection:** Configured real-time search indexing between Jira and Confluence to surface solutions and reduce inbound ticket volume.
* **SLA & Queue Orchestration:** Managed service desk priorities and response timers (SLAs) to ensure timely resolution of critical business issues.

---

## Technologies Used
* **Jira Service Management:** For incident intake, triage, and workflow automation.
* **Confluence:** For Knowledge Base hosting and technical documentation.
* **Atlassian Cloud:** Platform administration and cross-app integration.

---

## The Workflow: Step-by-Step

### 1. Designing the Intake Experience (Customer Portal)
I configured a standardized **Customer Portal** to streamline the reporting process. By creating specific request types for common issues like "VPN Connectivity," I ensured that the system captures all necessary technical data upfront, reducing the need for administrative follow-up.

<p align="center">
<img width="800" height="900" alt="Portal-Phase-1" src="https://github.com/user-attachments/assets/022e994c-cf7d-40cb-ad96-b97a3a0772d8" />

**Figure 1: I organized the Service Desk into high-level 'Portal Groups' (Hardware vs. Software) to simplify the user experience and ensure that requests are funneled into the correct high-level workflows from the start.**

<p align="center">
<img width="800" height="900" alt="Software-Group-Phase1" src="https://github.com/user-attachments/assets/9b8dc111-800c-4ecc-8ecf-7c6297f293d6" />

**Figure 2: A comprehensive view of the Request Types I configured within the Software Support group. Each type is mapped to a specific backend workflow, allowing for granular data collection and more efficient ticket triage.**

---

### 2. Proactive Ticket Deflection in Action
Once a solution was identified for the VPN issue, I authored a guide in **Confluence**. I then verified the **Shift-Left** integration: when a user types "VPN" into the portal, the system automatically "deflects" the ticket by suggesting the article immediately. This empowers the user to solve the problem without waiting for an agent.

<p align="center">
<img width="800" height="900" alt="Screenshot 2026-01-27 at 8 45 38 PM" src="https://github.com/user-attachments/assets/714f9b62-c2a2-4734-b5c9-0944c3abbae1" />

**Figure 3: The administrative view of the Knowledge Base article. I ensured proper indexing and space mapping within Jira Service Management to guarantee that the right documentation is surfaced to the right users.**


<p align="center">
<img width="800" height="900" alt="VPN_Article_Search_Phase3" src="https://github.com/user-attachments/assets/77fa76f1-7c47-4a39-9d3f-9abab44dc370" />

**Figure 4: Demonstrating the Shift-Left strategy. By integrating a Confluence Knowledge Base, the portal automatically suggests relevant articles as the user types, deflecting potential tickets before they are even submitted.**
  
<p align="center">
<img width="800" height="900" alt="VPN_Article_Phase3" src="https://github.com/user-attachments/assets/75482c57-095d-46a8-b0a1-28699a4a8543" />

**Figure 5: The end-user view of the "How-To" article. Providing clear, step-by-step troubleshooting steps for VPN connectivity empowers users to self-resolve, significantly reducing the volume of low-complexity tickets.**

---

### 3. Incident Triage & Professional Resolution
For cases where a ticket is still submitted, I managed the lifecycle as a Support Agent. This involved assigning the ticket, evaluating the priority/impact, and utilizing the Knowledge Base to provide a fast, standardized resolution to the end-user.

<p align="center">
<img width="800" height="900" alt="Ticket_Resolved_3_Phase4" src="https://github.com/user-attachments/assets/2df5bd9e-66a7-4a79-90f5-c183cad985df" />

**Figure 6: The Agent resolution interface. The red box highlights the detailed resolution comment I provided to the user, which includes a link back to the Knowledge Base article to prevent future recurring tickets (further reinforcing the Shift-Left strategy).**
  
<p align="center">
<img width="800" height="900" alt="Ticket_Resolved_Phase4" src="https://github.com/user-attachments/assets/926b96e2-7d3a-4436-931e-2f2308d6c605" />

**Figure 7: Final ticket status and SLA confirmation. The red circle shows the ticket marked as "Resolved." By processing the ticket efficiently, I demonstrated the ability to meet Service Level Agreements (SLAs) while ensuring the user received a professional and documented solution.**

## Project Conclusion: Technical Impact & Key Outcomes

This project successfully established a scalable ITSM framework centered on the "Shift-Left" methodology. By architecting a seamless integration between Jira Service Management and Confluence, I achieved the following technical milestones:

**Service Catalog Optimization**: Designed intuitive Portal Groups and Request Types to streamline the user intake process and ensure high data integrity for backend reporting.

**Ticket Deflection & Self-Service**: Leveraged Knowledge Base (KB) integration to surface relevant documentation at the point of entry, reducing the volume of low-complexity incidents.

**SLA Compliance**: Configured automated Service Level Agreements to monitor time-to-resolution, ensuring consistent delivery of support services within defined policy windows.

**End-to-End Lifecycle Management**: Demonstrated mastery of the full Incident Lifecycle, from initial intake and automated triage to agent resolution and post-incident documentation.

---

## Connect with Me
* **Name:** Brianne Young
* **LinkedIn:** https://www.linkedin.com/in/brianne-young0/
* **Email:** brianneyoung0@gmail.com
