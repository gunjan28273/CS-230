# CS-230
Portfolio Reflection – Draw It or Lose It Software Design
Client Overview and Software Requirements

The client for this project was The Gaming Room, a company that wanted to expand its existing Android game called Draw It or Lose It. The original version of the game only ran on Android devices, but the client wanted a new design that would allow the game to run across multiple platforms through a web-based application. The goal was to support desktop operating systems such as Windows, macOS, and Linux, as well as mobile devices.

The game itself is inspired by the television show Win, Lose, or Draw, where teams compete to guess a puzzle based on drawings that appear over time. Each game contains timed rounds where images gradually render as clues for players. Because the game is multiplayer and must support multiple teams and players simultaneously, the design needed to focus on scalability, reliability, and consistent gameplay timing. The system also needed to ensure that game names and team names were unique and that only one instance of the game could exist in memory at any given time. 

CS230_Project_Three_Completed (…

What I Did Well in the Documentation

One thing I believe I did particularly well in this project was evaluating the different operating platforms and explaining their strengths and weaknesses. I carefully analyzed Linux, Windows, macOS, and mobile platforms to determine how each could support the server side, client side, and development tools required for the application.

I also did a good job clearly explaining why Linux was the most appropriate choice for hosting the application because of its scalability, reliability, and cost efficiency. By connecting the technical platform choices directly to the client’s requirements, the document demonstrates a practical approach to system design that a development team could realistically implement.

How the Design Document Helped With Development

Working through the design document helped me organize the project before writing or implementing code. It forced me to think about architecture, system components, and how different parts of the application interact with each other.

For example, defining the domain model and system architecture helped clarify how the Game, Team, Player, and GameService classes should interact. Planning the design first made it easier to implement the singleton pattern and ensure that only one instance of the game service existed in memory. This type of structured planning reduces confusion during development and helps prevent major design changes later in the coding process.

What I Would Improve if I Revised the Project

If I could revise one part of the project, I would improve the system architecture section by adding diagrams that visually represent the three-tier architecture and distributed system components. While the document explains the architecture conceptually, diagrams showing the client layer, application servers, load balancers, and databases would make the design easier for stakeholders and developers to understand quickly.

Adding architecture diagrams and workflow visuals would also strengthen the documentation by making it more professional and easier for non-technical stakeholders to interpret.

Interpreting User Needs in the Design

When designing the system, I focused on interpreting the user’s needs by carefully reviewing the client requirements and translating them into technical design decisions. The Gaming Room wanted a solution that would allow players to access the game from multiple platforms and participate in real-time multiplayer gameplay.

To meet these needs, I designed the application as a web-based system with RESTful APIs, which allows different client devices to interact with the same backend services. I also recommended a scalable Linux server environment and cloud infrastructure to ensure the application could handle many simultaneous users. Considering the user’s needs is extremely important because software that does not align with the client’s goals or user expectations will ultimately fail, regardless of how well it is coded.

My Approach to Designing Software

When approaching the design of this software, I followed a structured process that included analyzing requirements, evaluating technology options, designing the architecture, and documenting the system components. This process helped ensure that each design decision aligned with the client’s goals and technical constraints.

In the future, I would continue using similar strategies, including requirements analysis, architectural planning, domain modeling, and platform evaluation. I would also incorporate additional techniques such as UML diagrams, architecture diagrams, and prototyping to better visualize the system before implementation. These strategies help create more scalable and maintainable software solutions.
