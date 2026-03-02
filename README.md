# CS255

  1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
    
  The DriverPass project was based on designing a system for a company called DriverPass. The client wanted to create a solution that fills a gap in driver education by offering students online classes, practice DMV tests, and optional in-person driving lessons. They needed a cloud-based, web-accessible system that would allow customers to register, purchase packages, schedule lessons, track their progress, and access updated DMV materials. The system also needed administrative controls so employees and the owner could manage reservations, track student and instructor information, control packages, and maintain security. Overall, it was a web-based learning and scheduling management system.
    
  2. What did you do particularly well?

  I believe I did particularly well in identifying both the functional and nonfunctional requirements of the system. I clearly outlined how the system should validate logins, handle password resets, enforce security measures like MFA, and lock accounts after failed login attempts. I also did a strong job detailing user roles and permissions, especially distinguishing between customers, employees, administrators, and IT staff. Additionally, I made sure to include performance expectations, platform compatibility, and cloud-based requirements, which are important for real-world implementation. 
    
  3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
    
  If I could revise one part of my work, I would improve the technical design section, especially the UML diagrams which were lacking according to feedback. While they identify the core system processes, I could add more detail to the sequence and class diagrams to better and more correctly show relationships between system components, such as how the database interacts with authentication and scheduling features. I would also refine some of the nonfunctional requirements by adding measurable metrics, such as clearer uptime percentages or more detailed scalability expectations. This would make the design more precise and closer to real-world development standards.
    
  4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

  I interpreted the user’s needs by carefully reviewing the interview transcript and identifying what problems DriverPass was trying to solve. For example, they needed a way to manage lesson scheduling, prevent overbooking, provide up-to-date DMV content, and track student progress. I translated those needs into specific functional requirements such as reservation tracking, package selection, authentication controls, and administrative access levels.

  Considering the user’s needs is extremely important because the system is ultimately built for them. If the system does not align with their workflow, business goals, or customer expectations, it will not be effective. Designing with the user in mind ensures the system is practical, efficient, secure, and easy to use. It also reduces the likelihood of costly redesigns later.
    
  5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

  I approach designing software by first gathering and analyzing requirements to fully understand the business problem. I separate functional and nonfunctional requirements to ensure both system behavior and performance expectations are addressed. From there, I create UML diagrams, such as use case, activity, sequence, and class diagrams, to visualize how the system will operate before any development begins.

   In the future, I would continue using structured requirement analysis, UML modeling, and possibly incorporate techniques like user stories and iterative design methods. I would also consider prototyping early in the process to gather feedback before finalizing system architecture. This approach helps ensure clarity, reduces risk, and leads to a more user-centered and efficient design.
