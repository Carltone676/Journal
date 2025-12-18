Client and Software Requirements

The client for this project was The Gaming Room, a company that originally offered Draw It or Lose It as an Android-only game application. The client wanted to expand the game into a web-based, multi-platform application capable of supporting multiple concurrent users, teams, and players. Key requirements included enforcing unique game and team names, supporting multiple teams per game, maintaining consistent game state across users, and ensuring that only one logical instance of the game management service existed at any given time. The goal was to design a scalable, maintainable solution suitable for a distributed environment.

What I Did Well

One of my strongest contributions in developing this documentation was clearly analyzing and justifying architectural decisions. I effectively evaluated multiple operating platforms and explained why a Linux-based server platform was the most appropriate choice for hosting the application. I also clearly documented how object-oriented principles and design patterns—such as the singleton and iterator patterns—were used to meet the client’s requirements. This resulted in a design that was both technically sound and easy for stakeholders to understand.

How the Design Document Helped With Development

Working through the design document was extremely helpful because it forced me to think through the system structure before writing any code. Defining the domain model, identifying constraints, and selecting appropriate design patterns early on reduced ambiguity and helped ensure that the implementation would align with the client’s needs. This structured approach made it easier to visualize class relationships, responsibilities, and data flow, which would directly support clean and maintainable code development.

What I Would Revise

If I could revise one part of the documentation, I would expand the System Architecture View section by adding a visual diagram or more detailed explanation of component interactions. While the written descriptions are clear, a higher-level architectural diagram showing client-server communication and data flow would further improve clarity for both technical and non-technical stakeholders.

Interpreting and Implementing User Needs

I interpreted the user’s needs by focusing on scalability, consistency, and ease of use. Requirements such as unique naming, centralized game management, and support for multiple concurrent users were implemented through careful use of data structures, design patterns, and server-side logic. Considering user needs is critical in software design because the success of an application depends on how well it solves real problems for its users while remaining reliable and intuitive.

Software Design Approach and Future Strategies

I approached software design using a top-down, iterative strategy, starting with requirements analysis and progressing through domain modeling, platform evaluation, and architectural decisions. In the future, I would continue using techniques such as UML diagrams, design patterns, and platform comparisons to analyze and design similar applications. I would also incorporate more early-stage feedback and prototyping to validate design assumptions before full implementation.
