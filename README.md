# DriverPass

**Summarize the project / who was the client / what system?**

The client was DriverPass, a company founded by Liam to help people pass their DMV driving test by offering better preparation than what was currently available. They wanted a cloud-based, web-accessible system that students could use to register accounts, schedule on-the-road driving lessons, take online classes, and complete practice tests. The system also needed to support staff roles—an IT admin, a secretary, and the owner—with role-based access, reservation tracking, activity logging, and a connection to the DMV for compliance updates.

**What did you do particularly well?**

I think I did a strong job translating a fairly loose, conversational interview into concrete, organized requirements. I separated functional from nonfunctional requirements clearly and made sure each functional requirement was specific and testable. My UML class diagram also came together well. I captured the key entities (User, Student, Secretary, Admin, Appointment, Driver, Car, Package, Practice Test, Account, and Activity Log) and used inheritance for the user roles, which kept the design clean and avoided duplicating shared attributes.

**One part you'd revise and how?**

If I could revise one thing, I'd improve the activity and sequence diagrams to show more of the alternate and error paths rather than just the main success flow.

**How did you interpret the user's needs, and why does it matter?**

I worked directly from the interview transcript, treating each thing Liam and Ian described as a need to be mapped to a requirement and then to a design element—for instance, their request to track "who made, canceled, or modified" a reservation became the Activity Log class and the audit/logging infrastructure. Considering user needs is critical as grounding the design in their needs is what keeps it useful, on-scope, and worth building.

**How do you approach designing software / future strategies?**

I approach design by first gathering and clearly documenting requirements, then modeling the system visually before any code is written, since diagrams expose gaps and relationships that are hard to see in prose. Going forward, I'd continue using UML and CASE tools like Lucidchart, but I'd lean more on checking each diagram back against the requirements and the client's words, and I'd validate my models with stakeholders earlier and more often to catch misunderstandings before they become expensive to fix.
