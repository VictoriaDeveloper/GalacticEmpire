# 🚀 Software Engineering Postmortem: Galactic Empire 🌌✨

🌠 1. Project Overview
Galactic Empire is a 4X strategy game where players lead their own galactic empire in a quest to dominate the stars. The gameplay revolves around mastering the four pillars of 4X strategy:

- Explore 🌍: Discover new planets.
- Expand 🏗️: Grow your empire through negotiation or conquest.
- Exploit ⚙️: Harness planetary resources to fuel your ambitions.
- Exterminate 💥: Wipe out hostile forces to secure dominance. Players choose from three unique races—Humans, Aliens, and Androids—each with their own leaders and bonuses, creating a dynamic and strategic playstyle. This project was created for the Foundry Jam - Found Your Own Indie Studio! with collaboration from nathonkepley.

🎯 2. Initial Project Goals
The main goal was to build a working prototype of a 4X game that emphasizes resource management and showcases how gameplay progresses across the four phases of 4X strategy.

Our user stories were centered around:

- Implementing the Explore, Expand, Exploit, and Exterminate phases 🌌.
- Designing a resource manager to reflect actions taken in each phase 💾.
- Providing a clear and engaging experience of a 4X game’s core mechanics 🛠️.

🛠️ 3. How Were the Goals Met?
We utilized the Agile development process to keep our project on track. Key methods included:

- Breaking down the project into user stories ✅.
- Organizing and tracking progress via a GitHub Kanban board 📋.
- Completing all core features, ensuring a functional prototype of the game. 🎮

🌟 4. What Went Well

- Gameplay Integration 🎮: The core phases—Explore, Expand, Exploit, Exterminate—worked cohesively, creating a seamless and enjoyable turn-based experience. Watching the empire grow and resources update dynamically was a major milestone.
- Aesthetics 🎶🖼️: The combination of visuals and music created an immersive experience, enhancing the overall gameplay.

⚠️ 5. What Went Wrong

- Asset Collection 🎨🚧: Finding assets that fit the space theme was difficult. This limitation forced us to use default or placeholder elements.
- State Management 🧩❌: When designing the planetary phases, I mistakenly implemented separate singletons for each phase, leading to a bloated and inefficient system.

💡 6. How Were the Challenges Addressed?

- UI/UX Assets 🖌️: I used Unreal Engine’s default UI components to create a clean and functional interface.
- Refactoring State Management 🔄: While individual singletons were a temporary solution, I plan to consolidate them into a single unified singleton in the future for cleaner and more efficient code .
📚 7. Lessons Learned
This project provided valuable insights and skills:

- UI/UX Design 🎨: Learned to use Unreal Motion Graphics (UMG) and Blueprint Visual Scripting to create interactive elements.
- Agile Development 🚀: Effectively applied Agile principles, including user stories and Kanban boards, for project organization.
- Code Optimization 🧑‍💻: Gained experience implementing and troubleshooting design patterns, particularly the Singleton Pattern.
🔮 8. Future Recommendations

- Enhanced Assets 🌌🎨: Invest time in finding high-quality space-themed UI/UX assets or design a new 4X game that aligns with the available assets.
- Code Refactoring 🔧: Refactor the game to use a single, unified singleton for better phase management and scalability.

✨ 9. Conclusion
Galactic Empire is a promising prototype that serves as the foundation for a larger, more polished project. Participating in the Foundry Jam provided an incredible opportunity to kickstart my dream of creating a full-fledged 4X strategy game.

This experience was invaluable, and I look forward to applying the lessons learned in future game development projects. 🚀 Thank you for joining me on this journey—let’s conquer the stars together! 🌠
