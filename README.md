
![Jira-Service-Management-logo](https://github.com/kirkgacias/jira-configuration/assets/158519921/0194198d-10a4-4ee1-b66b-929dc902f07d)

<h1> Jira Service Management: Ticket Lifecycle and Resolution </h1>

<p> In the rapidly evolving landscape of Information Technology (IT), the ability to efficiently manage and resolve service tickets is paramount for maintaining business continuity and ensuring user satisfaction. Jira Service Management is a robust IT service management (ITSM) tool by Atlassian that provides a comprehensive solution for tracking, prioritizing, and resolving IT service requests and incidents. This project, titled "Jira Service Management: Ticket Lifecycle and Resolution," aims to explore the functionalities offered by Jira Service Management in handling IT service tickets from inception to resolution. Through a hands-on approach, this project will delve into the various stages of the ticket lifecycle, demonstrating how Jira Service Management can streamline IT support processes, enhance communication, and improve service delivery within an organization.</p>

<h2>Objectives</h2>

<h4>Understand Jira Service Management: </h4>

- Gain a thorough understanding of Jira Service Management's interface, features, and capabilities, focusing on its application in IT service management.
  
<h4>Demonstrate Ticket Lifecycle Management: </h4>

- Showcase the complete lifecycle of a service ticket within Jira Service Management, including ticket creation, categorization, prioritization, assignment, resolution, and closure.
  
<h4>Implement Sample Ticket Scenarios: </h4>

- Simulate real-world IT service scenarios to demonstrate how different types of tickets (e.g., software bugs, hardware requests, and password resets) are handled within Jira Service Management.
  
<h4>Highlight Best Practices and Key Features: </h4>

- Emphasize Jira Service Management's key features, such as automation, SLA management, knowledge base integration, reporting, and how it can optimize IT support operations.


<h2>Technologies and Environments</h2>

- Jira Service Management 
- Windows 10

<h2>Ticket Lifecycle</h2>

![7b1f07f2-57bc-4103-83fa-841032dd2df9](https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/87e0ea11-099e-40cc-8a6c-b047dea3a1c5)

<br>

<p>The diagram shows the key stages a service ticket goes through from start to finish. It starts with Ticket Creation, where a user reports a problem. Next is Classification, where the ticket is sorted by type and priority. Assignment + Escalation follows, assigning the ticket to the right team and escalating it if needed. Resolution Steps involve fixing the issue, while Communication ensures the user stays updated. Finally, Resolution & Closure marks the problem as solved and closes the ticket. This flow ensures a smooth and organized approach to handling user issues.</p>

<h3>&#9312; Ticket Creation</h3>


<p>The service project portal is a user-friendly web interface designed for customers or employees to submit tickets (also known as requests or issues). Here's how to access and use it:</p>

- Accessing the Portal: Log in to your Jira Service Management instance. If you're an agent or an admin, you can access the portal by clicking on "Help Center" from the main dashboard or by navigating directly to the URL provided by your Jira administrator, which usually follows the format https://[your-domain].atlassian.net/servicedesk/customer/portals.

<br>

<img width="593" alt="Help Center" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/69bf8209-cac8-40bb-9485-49e8b5ef612c">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Submitting a Ticket:</strong> Once in the Help Center or specific service project portal, you can submit a ticket by selecting the appropriate request type (e.g., "Get IT help," "Report a problem," etc.). Fill out the form with the necessary details, such as a description of the issue, any relevant attachments, and other required fields.</p>

<img width="600" alt="reqs" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/52f60650-2705-4515-8eeb-dd01ddec254a">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Jira Service Management allows tickets to be created via email. Each service project can be configured with a unique email address that users can send their requests to, automatically creating tickets in the system.</strong></p>

<p><strong>Finding the Email Address:</strong> The email address for ticket submission is set up by the Jira administrator. You can usually find it in the project's settings under "Project settings" > "Email requests" or by asking your Jira administrator. It might also be communicated to users through internal channels or help documentation.</p>

<br>

<img width="550" alt="combine" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/a054bed9-1db9-4c83-9ac0-9ec7e9e02bc2">


<br>
<br>

<p><strong>Submitting a Ticket via Email:</strong> Simply send an email to the project's designated email address. The subject of the email typically becomes the issue summary, and the body of the email becomes the issue description. Attachments can also be included in the email and will be added to the ticket.</p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>&#9313; Classification </h3>

<p>The classification of tickets in Jira Service Management is a crucial step in the ticket lifecycle, as it determines how a ticket is handled, prioritized, and resolved. Classification involves categorizing the ticket based on its nature and urgency, which helps in streamlining the resolution process and ensuring that resources are allocated efficiently. Here's a detailed look at the key aspects of ticket classification:</p>

<h3>Types of Classification</h3>

<p><strong>Issue Type:</strong> This categorizes the ticket into predefined types such as Incident, Service Request, Problem, or Change. Each type has its own workflow and resolution process. To add, edit, or view issue types, go to Project Settings > Issue Types.</p>

<img width="600" alt="issue" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/e1dfbcf8-f496-4e69-9600-4420229de261">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Some common Issue types:</h3>

<p><strong>Incident: </strong>An issue impacting the user's ability to access or use services.</p>

<p><strong>Service Request:</strong> A request for something new, such as access to a service, additional resources, or information.</p>

<p><strong>Problem:</strong> An underlying issue causing multiple incidents.</p>
  
<p><strong>Change:</strong> A request for a significant modification to the system or services.</p>

<br>

<img width="700" alt="Incident" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/4f44817d-08d0-4575-a0b8-ad86bf8fd111">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Priority:</strong> Defines the urgency and impact of the issue, determining how quickly a ticket needs to be addressed. Priorities are usually defined as High, Medium, Low, or other custom levels set by the organization. Look for the "Priorities" section under issue attributes. This section will allow you to view, edit, add, or delete priorities. Below, you can see a list of configured priorities in your Jira instance.</p>

<p><strong>High:</strong> Issues that critically impact business operations or a large number of users and require immediate attention.</p>
  
<p><strong>Medium:</strong> Issues that affect a subset of users or can degrade the quality of service but aren’t immediately critical.</p>
  
<p><strong>Low: </strong>Minor issues with little to no immediate impact on business operations or user productivity.</p>

<br>

<img width="700" alt="prior" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/37d48b1b-ecb4-4e7b-a933-632cdf2c2417">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h3>Classification Process</h3>

<p><strong>Automated Classification:</strong> Utilize Jira Service Management's automation rules to classify tickets based on predefined criteria, such as keywords, requester information, or the source of the ticket. This speeds up the routing process and ensures consistency.</p>

<img width="700" alt="Automation" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/3e21de67-c27e-458a-b0b6-2a3f9177c25f">



<p><strong>Manual Intervention:</strong> In cases where automated classification is not possible or accurate, tickets should be manually reviewed and classified by a designated team member. This ensures that complex or unclear tickets are correctly categorized and prioritized.</p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h3>&#9314; Assignment and Escalation Section</h3>


<h3>Assignment Process:</h3>

<p><strong>Automated Assignment:</strong> Utilize Jira Service Management's automation rules to automatically assign tickets based on specific criteria such as issue type, priority, or expertise required.</p>

<img width="403" alt="Example 1" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/39c6f3a1-ee74-47fa-8a0b-35dc044e1d31">

<p><strong>The example above automates the assigning of a high-priority ticket to an administrator</strong></p>

<p><strong>Manual Assignment:</strong> In scenarios where automated assignment is not feasible or when a ticket requires special attention, the ticket can be manually assigned by a team leader or triage team</p>

<p><strong>Load Balancing:</strong> Consider the current workload of support staff when assigning tickets. Jira's dashboard and reporting tools can help managers monitor workloads and distribute tickets evenly to prevent burnout and ensure timely resolutions.</p>

<h5> Escalation Process</h5>

<p>Escalations are typically handled through a combination of issue priorities, automation rules, SLAs (Service Level Agreements), and workflows. These tools collectively enable you to define how and when an issue should be escalated</p>

- Setting Priorities: Priorities are set on issues to indicate their importance. You can define what each priority level means (e.g., Blocker, Critical, Major, Minor, Trivial) and use these to determine how quickly an issue needs attention.
  
- Configuring SLAs: SLAs are policies that define the expected time for responses and resolutions based on issue criteria, including priorities. You can set up SLAs to escalate issues that are close to breaching or have breached their expected resolution times. Navigate to Project settings > SLAs to configure these settings.

<img width="700" alt="SLA" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/390c56b5-c2eb-4797-9ea3-e3153dc2905c">



<h5>Automation Rules for Escalation</h5>

- Accessing Automation: Go to Project settings > Automation to view and create automation rules. Here, you can set up rules for escalating issues based on various triggers (e.g., time since creation, priority, comments). Like the previously shown example, you can set up an incident to be escalated to an administrator if the priority is set to high. 

<h5>Workflows for Escalation</h5>

- Customizing Workflows: Workflows define the lifecycle of an issue, including statuses and transitions. You can customize workflows to include escalation steps. Access this by navigating to Project settings > Workflows.

<img width="700" alt="workflow" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/4eea4610-fb25-46db-9c23-debfcbc826bb">



<h3>&#9315; Ticket Resolution </h3>

<p>The primary goal of the ticket resolution phase is to efficiently address and solve the user's issue or fulfill their request, adhering to the agreed Service Level Agreements (SLAs). This stage involves diagnosing the problem, identifying a solution, implementing the solution, and ensuring that the user is satisfied with the outcome</p>

<h3>Diagnosis and Investigation</h3>

<p><strong>Initial Assessment:</strong> Review the ticket details thoroughly to understand the issue or request. This might involve reproducing the issue, reviewing logs, or gathering additional information from the user.</p>

<img width="700" alt="Ticket details page" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/be2e80f8-232b-490a-8d1f-c374f3f6646f">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Utilize Knowledge Base:</strong> Check if there's a known solution or workaround in the knowledge base. Leverage past tickets and documentation for similar issues.</p>

<img width="700" alt="kb" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/583163a0-c872-4872-886d-6d5a27d4b79c">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h3>Solution Identification</h3>

<p><strong> Collaboration:</strong> Work collaboratively with team members or other departments if the solution requires cross-functional effort. Utilize Jira's commenting and @mention features to communicate within the ticket.</p>

<img width="700" alt="comment" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/523481aa-f13e-4368-b633-f1049a3ef143">


<h3> Implementation</h3>

<p><strong> Applying the Fix:</strong> Implement the solution, whether it's a configuration change, software update, hardware replacement, or providing detailed instructions to the user.</p>

<p><strong>Documentation:</strong> Document the steps taken to resolve the issue within the ticket for future reference and knowledge sharing.</p>

<img width="626" alt="documentation" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/139e7f0b-4fe9-4cb3-8142-1d40cbaee109">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3> Verification</h3>

<p><strong>User Confirmation:</strong> Ask the user to verify that the issue has been resolved to their satisfaction. This step is crucial to ensure that the ticket can be closed.</p>


<h3> Closure</h3>

<p><strong>Closing the Ticket:</strong> Once the user confirms the issue is resolved, close the ticket.</p>

<img width="500" alt="complete2" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/36a2fce6-cb59-48be-be99-3095ac65c09f">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Provide a summary of the resolution and any follow-up actions in the post-incident review.</strong></p>

<img width="700" alt="post incident" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/c2b73f62-50e4-454d-9937-100f0208a65e">


<h3>&#9316; Sample Ticket: Network Issue</h3>

<h5>Description:</h5>

<p>Starting this morning, the Marketing Department has been experiencing intermittent network connectivity issues. This has affected access to the internet and internal resources, leading to disruptions in the team's workflow. The network drops out approximately every 15 minutes and remains down for about 5 minutes each time. Users have tried reconnecting to the Wi-Fi and switching to wired connections with no improvement.</p>

<p><strong>Creation: </strong>A user submits a ticket reporting network connectivity issues in the Marketing department</p>

<img width="700" alt="Jie ticket" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/4646c1d1-ef47-4a36-9c81-8f7e5c04549b">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3> Classification:</h3>

<p><strong>Issue Type:</strong> Incident</p>
<p><strong>Priority:</strong> Moderate (Only affects one department)</p>
<p><strong>Service Category:</strong> Network Services</p>
<p><strong>Initial Support Level:</strong> Level 1 Support Team</p>


<img width="568" alt="network" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/d7731654-0aa4-4c2f-91f7-013a7f5b73f6">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3> Assignment + Escalation:</h3>

<p><strong>Assigned To:</strong> Network Specialist, Level 1 Support Team</p>
<p><strong>Escalation Path:</strong> If unresolved within 2 hours or reoccurs within the same day, escalate to Level 2 Network Support Team.</p>

<img width="328" alt="lvl1" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/56fd85fd-f722-42b7-92f7-a54e1d42ae4d">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3> Resolution Steps:</h3>

<p><strong>Diagnostic Steps:</strong> Checked network error logs, tested the stability of the connection on multiple devices, and monitored for hardware malfunctions.</p>
<p><strong>Resolution Attempt:</strong> Reset networking equipment and updated firmware. Monitored for stability over a 2-hour period.</p>

<img width="700" alt="net switch" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/91e833bd-8038-4d31-94fd-7e9122112ba9">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Resolution & Closure:</h3>

<p><strong>Final Resolution:</strong> After resetting did not provide a long-term solution, replaced a faulty network switch identified during further diagnostics.
</p>
<p><strong>Verification:</strong>Network stability was confirmed by the Marketing Department over a 24-hour period.</p>
<p><strong>Closure:</strong> The ticket was officially closed after confirmation of the resolution, and feedback was requested regarding the handling of the issue.</p>

<img width="700" alt="lasy" src="https://github.com/kirkgacias/jira-ticket-lifecycle/assets/158519921/6e0dc2bb-1da2-447b-bcfb-4408e5da37ca">

<h2> Final Thoughts and Conclusion</h2>

<p>This project took us through each critical phase, from the initial report to the final resolution. It presented how effective classification, timely assignment, and clear communication contribute to efficient problem-solving. By applying best practices at each stage, we ensure a smooth and effective IT support process.</p>

<p>In conclusion, mastering the ticket lifecycle in Jira Service Management enhances the support team's ability to resolve issues promptly. With a robust system like Jira, we can streamline IT services, minimize disruptions, and maintain a high level of user satisfaction.</p>

<h1>Thank you! &#127881; </h1>


