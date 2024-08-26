# snhu-assignments

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room is the client that wanted a web-based game application designed called "Draw It or Lose It". Their requirements were:

- Manage multiple teams with unique names
- Ensure each team has multiple players
- Maintain one instance of the game in memory at any given time
- Provide an easy to use interface for end users
- Ensure the web app can handle image transitions, timers, and real-time interactions
- Make the web app scalable to handle varying traffic loads and be deployable across multiple environments.

2. What did you do particularly well in developing this documentation?

In the documentation I covered the aspects of the software design platform, including:
- Clearly defining the technical and business requirements
- Identifying the relevant design constraints around scalability, latency, and security
- Outlining the high-level system architecture, including the tiers, components, and logical/physical topology
- Providing a detailed domain model to illustrate the key entities and their relationships
- Thoroughly evaluating the advantages and challenges of different operating platforms (Mac, Linux, Windows, mobile)
- Making well-reasoned recommendations on the overall architecture, including the use of Linux, auto-scaling, load balancing, distributed systems, and security considerations.

3. What about the process of working through a design document did you find helpful when developing the code?

Going through the exercise of developing a comprehensive design document helped me to:
- Thoroughly define and understand the problem and requirements upfront
- Identify potential architecture and design tradeoffs early on
- Map out the core entities, relationships, and business logic before coding
- Anticipate scalability, performance, and security challenges that would need to be addressed
- Provide a clear roadmap and framework to guide the actual implementation

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

One area that could potentially be improved is the "Evaluation" section, which is where I compare the different operating platforms. I could’ve:
- Considered additional factors like cost, maintenance, community support, and future roadmaps for each platform.
- Potentially adding a scoring matrix or decision framework to make the platform selection process more structured and transparent.

This would help reinforce the rationale for the final Linux recommendation and make the evaluation more comprehensive.

5. How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

The software design clearly took the user's needs into account in several ways:

- Defining the business requirements around providing a simple interface, ensuring smooth game flow with timers and image transitions, and delivering a scalable and responsive web application.
- Structuring the system architecture to separate the concerns of the presentation, application, and data tiers - ensuring a clean separation of concerns and optimized user experience.
- Considering cross-platform compatibility and development tool support for different operating systems to maximize accessibility.
- Prioritizing security, performance, and scalability to create a reliable and high-quality user experience.

Considering the user's needs is critical because the software is ultimately designed to serve them. Being ignorant to their requirements and pain points will lead to a product that fails to meet their expectations and is unlikely to be successful.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

The approach taken in this software design document was working backwards from the customers need. I:

1. Clearly define the problem statement, requirements, and constraints upfront.
2. Develop a high-level system architecture and logical/physical topology.
3. Model the core entities and their relationships using a domain model.
4. Evaluate the tradeoffs of different technology platforms and make recommendations.
5. Address key non-functional requirements like scalability, performance, and security.

In the future, I would continue to leverage similar techniques, such as:

- Architectural modeling using diagrams, UML, and other visual tools.
- Evaluating technology options through research, prototyping, and decision frameworks.
- Addressing non-functional requirements through proven design patterns and best practices.
