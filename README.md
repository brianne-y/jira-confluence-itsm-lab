# Jira Service Management Help Desk Simulation

## Overview

Configured a Jira Service Management instance to simulate an MSP (Managed Service Provider) help desk environment. This project covers the full incident management workflow: customer portal setup, SLA configuration with timed response and resolution targets, ticket lifecycle management from intake through resolution, and Knowledge Base development in Confluence for ticket deflection.

## Tools Used

- **Jira Service Management** — ITSM platform used to manage the help desk portal, incidents, and SLA tracking
- **Confluence** — Documentation platform integrated with Jira, used to build Knowledge Base articles
- **SLA Management** — Configured timed response and resolution targets for incident prioritization

---

## What I Did

### 1. Configured the Customer Portal

Set up a customer-facing portal where users can submit support requests by category. Configured request types and routing rules so that incoming tickets are automatically categorized and assigned to the appropriate queue. This is the first point of contact between end users and the help desk.

![Customer Portal](img/01_customer_portal.jpg)
*Customer portal interface — users select their issue type to submit a support request, which is automatically categorized and routed to the correct queue.*

---

### 2. Configured SLAs (Service Level Agreements)

Set up SLA definitions with timed targets for both response and resolution. Each incoming ticket triggers an SLA timer based on its priority level — ensuring that high-priority incidents are acknowledged and resolved within defined windows. SLA compliance is tracked in real time on each ticket.

<table>
  <tr>
    <td><img src="img/02_sla_setup.jpg" width="450"/></td>
    <td><img src="img/03_sla_timer.jpg" width="450"/></td>
  </tr>
  <tr>
    <td><em>Left: Configuring the "Time to Resolution" SLA with a 2-hour target.</em></td>
    <td><em>Right: Live SLA timer counting down on an active ticket, showing remaining time to meet the resolution target.</em></td>
  </tr>
</table>

---

### 3. Managed the Incident Lifecycle

Practiced the full ticket workflow from intake through resolution. Each ticket moves through defined states — **To Do → In Progress → Resolved** — with updates documented at each stage. User-facing comments keep the caller informed of progress, while internal notes document the technical troubleshooting process.

<table>
  <tr>
    <td><img src="img/04_ticket_in_progress.jpg" width="300"/></td>
    <td><img src="img/04b_user_update.jpg" width="300"/></td>
    <td><img src="img/05_ticket_resolved.jpg" width="300"/></td>
  </tr>
  <tr>
    <td><em>Left: Moving a ticket to "In Progress" to begin troubleshooting.</em></td>
    <td><em>Middle: Posting a customer-visible comment to keep the user informed.</em></td>
    <td><em>Right: Marking the ticket as "Resolved" after confirming the fix.</em></td>
  </tr>
</table>

---

### 4. Built a Knowledge Base in Confluence

Integrated Confluence with Jira Service Management to create a Knowledge Base for common issues. Authored a VPN troubleshooting guide with a structured Problem/Solution format. When users submit tickets related to VPN issues, the portal automatically suggests relevant Knowledge Base articles — reducing ticket volume by enabling self-service resolution (ticket deflection).

<table>
  <tr>
    <td><img src="img/06_kb_creation.jpg" width="450"/></td>
    <td><img src="img/07_kb_search.jpg" width="450"/></td>
  </tr>
  <tr>
    <td><em>Left: Creating the Knowledge Base space in Confluence.</em></td>
    <td><em>Right: The portal automatically suggesting the VPN troubleshooting article when a user types "VPN" in their ticket description.</em></td>
  </tr>
</table>

![VPN Guide](img/08_vpn_guide.jpg)
*Published Knowledge Base article: VPN troubleshooting guide with structured Problem and Solution sections, authored for both technician reference and end-user self-service.*

---

## Key Takeaways

- **Ticketing System Proficiency** — Experienced with the full incident lifecycle in Jira Service Management: creation, triage, assignment, troubleshooting, documentation, and resolution
- **SLA Management** — Understand how priority-based SLA timers drive response and resolution targets, and how to work within those windows
- **Customer Communication** — Practiced keeping users informed throughout the ticket lifecycle with clear, professional status updates
- **Documentation & Knowledge Management** — Built Knowledge Base articles that standardize troubleshooting procedures and enable ticket deflection through self-service
- **Process Orientation** — Learned that effective IT support is about structured workflows and clear communication, not just technical fixes
