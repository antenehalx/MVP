This is MVP readme file for my portifolio project.

Build my portfolio project: 



0. Project progress!

Creating a 3D maze game using raycasting and SDL2 is a challenging but rewarding endeavor. Raycasting is a technique used to render a 3D environment in a 2D window by casting rays from the player's viewpoint and determining what they hit. Here's a detailed breakdown of the challenges i might encounter during different stages of the maze project:

1. SDL2 Setup and Window Creation:
    Challenge: Setting up the SDL2 library and creating a window for rendering can be the first hurdle. I'll need to handle events, manage the game loop, and set up the rendering context.
    Solution:  Follow SDL2 documentation and tutorials to initialize the library, create a window, and set up the rendering context properly.

2. Raycasting Basics:
   - Challenge: Understanding the basics of raycasting, such as how to cast rays from the player's viewpoint and calculate intersections with walls.
   - Solution: Study online resources and tutorials that explain the principles of raycasting. Understand the math behind casting rays and detecting wall intersections.

3. Map Representation:
   - Challenge: Designing a map representation that defines the layout of the maze. This could be a grid or a more complex data structure.
   - Solution: Choose a suitable data structure to represent the maze, such as a 2D array. Define walls, open spaces, and other elements of the maze within this structure.

4. Ray-Grid Intersection:
   - Challenge: Implementing the ray-grid intersection algorithm to determine which cell the ray hits.
   - Solution: For each ray, step through the grid cells based on the ray direction and check for intersections with walls. Keep track of the distance to the nearest wall in each direction.

5. Wall Drawing:
   - Challenge: Rendering the walls on the 2D window based on the raycasting results. This involves calculating wall height and positioning.
   - Solution: Use the distance to the wall to calculate its height on the screen. Map the height to the screen space and draw the wall column by column.

6. Textures and Mapping:
   - Challenge: Adding textures to the walls to make the environment look realistic.
   - Solution: Load texture images and map them onto the wall surfaces based on the intersection points calculated during raycasting.

7. Optimizations:
   - Challenge: Raycasting can be computationally intensive, especially if done inefficiently. Optimizing the algorithm for better performance is crucial.
   - Solution: Implement optimizations such as limiting the number of rays, using techniques like "fisheye" correction, and avoiding redundant calculations.

8. Player Movement and Controls:
   - Challenge: Implementing player movement and controls in the 3D maze environment.
   - Solution: Handle user input to move the player within the maze, updating the player's position and direction accordingly.

9. Collision Detection:
   - Challenge: Preventing the player from walking through walls by implementing collision detection.
   - Solution: Check the player's position against the maze map to ensure they don't move into wall cells.

10. Adding Features:
    - Challenge: Implementing additional features like doors, keys, enemies, and other gameplay elements.
    - Solution: Extend my maze engine to incorporate these features, adjusting the raycasting and game logic accordingly.

Challenges are part of the learning and development process. Each of these challenges will provide valuable learning opportunities as my progress with my maze project. I’ll Make use of online resources, tutorials, forums, and experimentation to overcome these challenges and create a fully functional 3D maze game using raycasting and SDL2.
 
While the project is heavily focused on technical challenges, there can be several unexpected non-technical challenges that might arise during its development. Here are a few examples:

1. Time Management:
   - Challenge: Balancing the project with other commitments like school, work, or personal life can be challenging. Developing a game requires a significant time investment.
   - Solution: Plan a realistic schedule and allocate time for different project tasks. Set milestones and goals to track progress and avoid last-minute rushes.

2. Motivation and Burnout:
   - Challenge: As the project progresses, there might be moments of low motivation or burnout, especially if when encounter technical roadblocks or repetitive tasks.
   - Solution: Take regular breaks, celebrate small victories, and remind myself of the excitement of the end product. Engage in activities that rejuvenate my mind.

3. Scope Creep:
   - Challenge: Overambitious goals or constantly adding new features can lead to scope creep, where the project becomes larger and more complex than initially planned.
   - Solution: Define a clear scope and stick to it. Prioritize essential features and save additional ideas for a future version or iteration of the game.

4. Team Collaboration (if applicable):
   - Challenge: When working with a team, communication and collaboration can be challenging. Differences in opinions, misunderstandings, or conflicting schedules can arise.
   - Solution: Maintain open communication, establish clear roles and responsibilities, and address conflicts early. Tools like version control and project management software can help streamline collaboration.

5. Creativity and Design Choices:
   - Challenge: Designing the maze layout, visual aesthetics, and gameplay mechanics can be creatively challenging. Striking a balance between visual appeal and playability is crucial.
   - Solution: Research game design principles, gather inspiration from other games, and seek feedback from others to refine my design choices.

6. User Experience and Playtesting:
   - Challenge: Ensuring that my game is enjoyable and intuitive for players can be difficult. I might overlook aspects that are clear to me but confusing to players.
   - Solution: Conduct playtesting with people who haven't been directly involved in the development. Their feedback can help you identify usability issues and areas for improvement.

7. Scope Realization:
   - Challenge: Realizing that the scope i initially envisioned might not be achievable within my current skill level or timeframe can be disheartening.
   - Solution: Be prepared to adapt and scale down my ambitions if necessary. Focus on delivering a polished, functional experience withinmy capabilities.

8. Technical Learning Curve:
   - Challenge: As i’m new to certain technologies or concepts, the learning curve can be steeper than expected, leading to frustration.
   - Solution: Approach each challenge as a learning opportunity. Break down complex concepts into smaller parts and gradually build my understanding.


9. Testing and Debugging:
   - Challenge: Identifying and fixing bugs, especially those that only appear under specific conditions, can be time-consuming and frustrating.
   - Solution: Develop a systematic approach to testing, create debugging tools, and consider using testing frameworks to streamline the process.

10. Perfectionism:
    - Challenge: Striving for perfection in every aspect of the project can lead to never-ending refinement and delays.
    - Solution: Aim for a balance between quality and completion. Remember that a project is never truly finished, and there will always be room for improvement.

Addressing these non-technical challenges requires a combination of self-awareness, adaptability, and good project management practices. By recognizing and preparing for these challenges, you can navigate them more effectively and ultimately create a successful maze game project.
 
If you're working on your maze project without the assistance of friends or a team, you can still discuss collaboration and communication aspects in your project documentation, reports, or presentations. Here's how you might address this:

Collaboration:
Even though i'm working independently, i can mention potential collaboration points that i would have pursued if i had friends or team members involved:

1. Collaborative Ideas: Explain how brainstorming and idea-sharing sessions with friends could have led to innovative gameplay mechanics, level designs, or visual elements.

2. Feedback Loop: Describe how i would have sought feedback from friends at different stages of development to gather diverse perspectives and refine your ideas.

3. Skill Synergy: Mention how having friends with different skill sets could have allowed me to allocate tasks based on individual strengths, potentially improving efficiency.

Communication:
While direct collaboration might not be happening, communication with myself and potential future players is still vital:

1. Clear Documentation: Emphasize the importance of maintaining clear and detailed documentation of my project's progress, decisions, and coding logic. This documentation can serve as a communication tool for anyone reviewing my work in the future.

2. User-Centric Approach: Explain how i considered the needs and preferences of players even if i don't have direct collaborators. Describe how you're making design decisions with potential players in mind.

3. Open to Feedback: Mention that even though i'm not working in a team, i'm open to feedback from external sources, like online forums, gaming communities, or mentors. This showcases your willingness to engage in a broader conversation about your project.

4. User Testing: Discuss my plans for involving others, such as friends or testers, in playtesting my game. Explain how user testing can provide insights into the user experience and highlight areas for improvement.

5. Sharing Progress: If i'm active on social media or have a personal blog/portfolio, i'll mention how my  progress with a wider audience. This could potentially lead to online interactions and feedback.

While i may not have direct collaborators, effective communication and collaboration practices can still be demonstrated through my planning, decision-making processes, documentation, and openness to input from external sources.

Project Updates


1. Project Description:
   - Change:  Refine and expand the project description to provide a clear overview of the project's goals, technologies used, and its significance.
   - Reasoning:  A well-written project description helps viewers quickly understand what the project is about and why it's valuable. It should capture attention and generate interest.

2. Detailed Technical Overview:
   - Change:  Add a section that goes deeper into the technical aspects of the project, explaining the architecture, algorithms used, and any innovative solutions.
   - Reasoning: Demonstrating my technical skills and problem-solving abilities can impress potential employers or collaborators. It also provides insights into my thought process.

3. Screenshots and Visuals:
   - Change: Incorporate more screenshots, images, or even short videos showcasing different aspects of the project, such as UI/UX, gameplay, or visual effects.
   - Reasoning: Visuals help convey the project's aesthetics and functionality. They make my portfolio engaging and offer a quick glance at my project's visual appeal.

4. Code Samples:
   - Change:  Include snippets of my project's code, highlighting well-structured and innovative portions.
   - Reasoning: Sharing code samples gives potential employers or collaborators an insight into my coding style, best practices, and problem-solving skills.

5. Challenges Faced and Solutions:
   - Change: Describe challenges i encountered during the project and how i was overcame them.
   - Reasoning: Demonstrating how i was handle challenges and adapt to unexpected obstacles showcases your resilience and problem-solving capabilities.

6. Lessons Learned:
   - Change: Add a section reflecting on the lessons you learned from the project, both technically and professionally.
   - Reasoning: This shows your growth and ability to reflect on experiences, making you a more well-rounded candidate or collaborator.

7. User-Centered Approach:
   - Change: Highlight any user-centric design decisions i made and explain how you considered the user experience.
   - Reasoning: User-centered design demonstrates my ability to create projects that meet users' needs and preferences, which is crucial in many industries.

8. Future Enhancements:
   - Change: Discuss potential future enhancements or features i would add to the project if i had more time or resources.
   - Reasoning: This shows my forward-thinking mindset and my commitment to continuous improvement.

9. Impact and Use Cases:
   - Change: Add a section explaining the potential impact of my project and the real-world use cases it addresses.
   - Reasoning: Demonstrating the practical applications of my project makes it more appealing to viewers who might be looking for solutions to similar problems.

These changes are just suggestions, and the final decisions depend on my project's nature and goals. My portfolio should effectively showcase my skills, achievements, and the value you bring as a developer or professional. Regularly updating and refining my portfolio is essential as my skills and experiences evolve.


Progress
 
On a scale of 1 to 10, i would  rate the progress i’ve made this week = 9
How are you measuring your progress? 
My progress = progressive.
Discuss why you have given your team (or yourself) this rating.
Cause i've been working day and night and i deserve it.
Provide an assessment of whether your project will be completed on time as specified in your Project Proposal and MVP definition. 
Current Status Evaluation.
Task Completion Rate.
Remaining Work Analysis.
 Unforeseen Challenges.
Mitigation Strategies.
Communication.
Stakeholder Expectations.
Revised Timeline.
Risk Assessment.
   Thos are my progress.





