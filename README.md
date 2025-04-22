# CS-230-Operating-Platforms

## Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room is the developer of Draw It or Lose It, a game where teams compete to guess words or phrases based on drawn images. Currently available only on Android, they wanted to expand the game into a web-based, multi-platform application that could support multiple teams and players. They asked for a design that supports unique game and team names, ensures only one instance of the game in memory and runs effectively across desktop and mobile platforms.

## What did you do particularly well in developing this documentation?
I think I did a great job clearly breaking down the software requirements and translating them into a clean, structured design document. I explained technical concepts like the Singleton and Iterator design patterns in an accessible way that both developers and clients could understand. I also made sure to include real-world considerations like scalability, security and cross-platform compatibility, which are crucial in any distributed application.

## What about the process of working through a design document did you find helpful when developing the code?
Writing the design document first helped me lay a strong foundation for the code. It allowed me to think ahead about how the classes and objects would interact, what responsibilities each component should have and how to handle key constraints like unique identifiers and memory limitations. It made the coding process much smoother because I wasn’t constantly second-guessing the structure as I already had a plan.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part, it would be the System Architecture View section. I left it as a placeholder, but in a real-world project, it would be important to visually and technically explain the system components, such as load balancers, web servers, databases and how they communicate. I’d like to add a logical diagram showing the flow between front-end clients, the server and the storage/database layers.

## How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I started by focusing on what mattered most to the user which is a fun, fast and fair multiplayer experience. That meant implementing real-time image rendering, unique game/team names and secure, scalable communication between clients and the server. Understanding the user's experience helped guide decisions around responsiveness, security and memory efficiency. It's crucial to keep the user in mind because they’re the ones who will ultimately judge the success of the software, not just by how well it works, but by how enjoyable and intuitive it feels.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the design by identifying patterns early (like Singleton for memory management and Iterator for collections), and by outlining the domain model with inheritance to reduce redundancy. I’ll continue using UML diagrams, requirement breakdowns, and software patterns in future projects. These strategies help me stay organized and ensure that every design decision ties back to what the user needs and what the system requires to perform well under real-world conditions.
