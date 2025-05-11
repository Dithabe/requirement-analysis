# requirement-analysis
Requirement Analysis in Software Development

In every software development project, proper requirements analysis is vital for the successful deployment of the project.
This repository serves as a layout for the requirement analysis process in a project.

<h2>What is Requirement Analysis?</h2>
<p>Requirements analysis is a crucial phase in software development lifecycle (SDLC) where the project gathers,
analyzes, and defines the requirements of the software product to be developed.</p>

<h2>Why is Requirement Analysis Important?</h2>
<p>In the SDLC process, requirements analysis is important as it:</p>
<ul>
  <li>Aids in clarity and understanding of what the stakeholder needs are</li>
  <li>Clearly defines the scope of the project, preventing scope creep</li>
  <li>Provides a solid foundation for designing and developing systems</li>
  <li>Facilitates accurate estimation of project cost, resource, and time</li>
</ul>

<h2>Key Activities in Requirement Analysis</h2>
<ul>
  <li>Requirement Gathering - using interviews, surveys, and workshops to collect initial requirements from stakeholders.</li>
  <li>Requirement Elicitation - Refining and elaborating on the gathered requirements through brainstorming, focus groups, and prototyping techniques</li>
  <li>Requirement Documentation - Using requirement specification documents, user stories, and use cases to capture the requirements in a detailed and structured format.</li>
  <li>Requirement Analysis and Modeling - Creating models to visualize and understand requirements</li>
  <li>Requirement Validation - The review and validation of the requirements with stakeholders in addition to defining the acceptance criteria to ensure traceability</li>
</ul> 

<h2>Types of Requirements</h2>
<h3>Functional Requirements</h3>
<p>Functional requirements describe what the system should do. For the case study provided, these are the functional requirements:</p>
<ul>
  <li>Hotel Management Service - The hotel managers/owners will be using this to manage hotel related information and services</li>
  <li>Customer Service (Search + Booking) - Here, customers can search and book a hotel</li>
  <li>Property listings/View Booking Service - a customer can view old and current bookings on the app.</li>
</ul>
<h3>Non-functional Requirements</h3>
<p>Non-functional requirements describe how the system should perform. FOr the case study provided, these are the non-functional requirements:</p>
<ul>
  <li>Performance and Reliability - Content Delivery Network (CDN) and Message Queue Systems have to work together to provide fast delivery on Internet content</li>
  <li>Usability - The CDN app shows the content to customers like nearby hotels, recommendations, and offers</li>
  <li>Scalability - Archiving of old data, increasing the database (to handle increased queries) and handling a high volume of data is done with various Database Management Systems</li>
  <li>Performance - Through Redis, a caching server, requests made for recent data is readily available reducing the loading time on the app side</li>
</ul>

<h2>Use Case Diagrams</h2>
<p>Use case diagrams serve as visual representation of interactions between users and the system. in the diagrams, identity actors such as guests or registered admin users get to interact with several use cases such as searching and booking of the desired properties</p>
<p>Benefits of Use Cases Diagrams:</p>
<ul>
  <li>They provide a clear visual representation of system functionalities</li>
  <li>They help in identifying and organizing system reqiurements</li>
  <li>They facilitate communication among stakeholders and development team</li>
</ul>

![alx-booking-uc](https://github.com/user-attachments/assets/4f16c198-5620-40f6-9797-e67379356041)


<h2>Acceptance Criteria</h2>
<p>Acceptance criteria is needed to establish clear criteria for feature completion. It defines what is referred to as "Done" in a project or in sub-tasks related to a project thereby maintaining quality and meeting user expectations.</p>
<p>An example of acceptance criteria: "In the checkout journey of the booking process, a user must be able to select the arrival and departure dates from a drop-down calendar option. The selected dates should further be displayed on the reservation page and on the order confirmation email."</p>


