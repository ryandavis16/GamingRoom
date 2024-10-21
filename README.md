# The Gaming Room Software Design

## Questions and Answers

### 1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client for this project was The Gaming Room, a company that wanted to develop an Android game app called "Draw It or Lose It." The idea for the game was based on an older game from the 1980s, but the new version would involve rendering images instead of having contestants appear in person. The requirements included support for team play, where multiple teams and players could participate, and the ability to manage game instances so that only one game could run in memory at a time. The software needed to be scalable across different platforms, including Windows, macOS, Android, and iOS, with strong emphasis on security and data consistency.

### 2. What did you do particularly well in developing this documentation?

In developing the documentation, I did a good job of outlining the requirements clearly and considering various factors, like scalability, cross-platform compatibility, and security. The design included recommendations for specific technologies, such as using Linux for the server-side due to its stability and scalability, which provided a solid foundation for the game. Additionally, the evaluation of different platforms and their pros and cons helped ensure that all potential challenges were addressed. This thorough approach made it easier to understand the project’s requirements and determine the best solutions.

### 3. What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped clarify the project's scope and requirements, which made it easier to develop the code. It allowed me to anticipate potential issues, such as platform-specific limitations, and plan solutions ahead of time. Documenting the requirements also made it clear what the core functions needed to be, guiding the development process step by step. By addressing things like memory management and security in the document, I was able to keep those concerns in mind while coding, resulting in a more efficient workflow.

### 4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work on the documents, I would focus on the security section. Although I covered various security measures, such as encryption and role-based access control, I could have gone into more detail about specific implementation steps. Adding information on handling potential threats, like distributed denial-of-service (DDoS) attacks or data breaches, would strengthen the recommendations. I would also include more examples of best practices for securing user data to ensure the design provides maximum protection.

### 5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by emphasizing scalability, security, and cross-platform compatibility, which were key requirements for the game. This guided the choice of technologies, such as using cloud services like AWS for backend support and PostgreSQL for data management. Considering the user’s needs ensured that the final design could handle a high number of players without compromising performance. Addressing user requirements is crucial in software design because it determines how well the final product will meet their expectations and adapt to future growth.

### 6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach to designing the software involved first identifying the key requirements and then mapping out how each component would interact. I used strategies like evaluating different operating systems to determine the best fit for server and client needs and recommended specific architectures like x86_64 for server performance. In the future, I would continue to use a similar approach, with more emphasis on prototyping and user feedback, to refine the design. Additionally, I would incorporate agile methods to allow for iterative improvements based on testing and user input.
