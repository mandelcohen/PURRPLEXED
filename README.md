![Purrplexed Logo Gray](https://github.com/user-attachments/assets/96537b58-15fd-4f35-a1e2-1995c1d3b5d2)

## Game Description
**PURRPLEXED** is a creative puzzle-solving game where players guide a unique team of cats—each with distinct personalities and abilities—through a series of intricate challenges. From the **Scaredy Cat**, who scratches through obstacles despite its timid nature, to the slow but powerful **Lazy Cat**, each feline offers strategic options for overcoming puzzles. As you progress, your clowder grows, expanding your tactical choices and unlocking new methods to tackle increasingly complex challenges.

Developed using **Unreal Engine 5**, PURRPLEXED leverages the engine's power for advanced **AI** through **Behavior Trees** and **Blackboard** for precise, personality-driven behavior. Created entirely with **Blueprints**, the game’s design is efficient and scalable, providing both flexibility and potential for future content. The **Landscape tool** enriches the environment, while **Custom Components** enhance puzzle mechanics and cat interactions, ensuring an engaging gameplay experience supported by a polished and accessible **UI**.

**Created by: August Lewén, Mandel Cohen & Sam Abou-Gabal**

[![Play PURRPLEXED on itch.io](https://img.shields.io/badge/Play_on-itch.io-red?style=for-the-badge&logo=itch.io)](https://bittersweetalmond.itch.io/purrplexed)


### Watch the trailer on YouTube by clicking the image below:
[![Watch the trailer](https://img.youtube.com/vi/JQ9lg9llYRE/maxresdefault.jpg)](https://youtu.be/JQ9lg9llYRE)


## Development Process

Our team leverages a variety of tools and methods to stay organized and collaborative throughout the development process. We use Miro and Trello for visual communication and project management. Each week, we begin with a sprint planning session and conclude with a retrospective to assess progress. Daily scrum meetings keep us aligned, and we've added a re-prioritization meeting every Wednesday as an outcome of our first retrospective.

We maintain continuous communication, assisting one another through pair programming when necessary. On the first day, we established a clear project folder structure and agreed on naming conventions, as well as key technical design patterns, including event dispatchers, inheritance, object-oriented programming (OOP), and a component-based architecture.

Throughout this project, we’ve learned that working with AI is both challenging and rewarding. Trello has been essential for keeping track of tasks, understanding priorities, and meeting weekly milestones. We’ve become better at splitting larger tasks into smaller, more manageable ones, and testing together daily has been a crucial part of our process. By the end, we’ve gained confidence in using Unreal Engine 5 and are proud to add this project to our portfolios.

![Purr_Gameplay2](https://github.com/user-attachments/assets/81b943bf-623c-4154-9417-cd513870db59)

## Game Mechanics Summary

- Players can hover and click the mouse to see which objects cats can interact with, using a custom component. 
- Lazy cats headbutt objects while Scaredy cats scratch them to clear a path. 
- All cats share a general click-to-move task, navigating via a nav mesh, with movement dynamically updated when new target points are set. 
- Cats can be selected either by clicking on them in the level or through the HUD, which toggles a selection circle and synchronizes the HUD display.

![Purr_Gameplay1](https://github.com/user-attachments/assets/300abacf-f8db-4380-828a-01fac6e11a52)

## AI Cat Behaviors

In our project, we utilize Behavior Trees, custom AI tasks, Blackboard keys, and AI Perception components to give each cat its own unique behavior. Depending on what they perceive—whether it's a threat or catnip—their actions dynamically adapt, creating engaging and varied interactions within the game.

Both Lazy and Scaredy have AI Perception, which sets their primary (leftmost) branch in the Behavior Tree to true based on what they detect. The next step involves evaluating the cat’s behavior type: if the primary Boolean for IsScared or IsLazy is false, and the player clicks on a valid interactable component, Scaredy will perform a scratching action, while Lazy will headbutt the object to interact with it. If neither condition applies, the system defaults to the third option, where the cat can move to the target point, following a basic click-to-move behavior.

This layered system allows for flexible AI responses based on the context, making the gameplay dynamic and responsive.

### Lazy Cat:
<img width="1587" alt="BT_Lazy" src="https://github.com/user-attachments/assets/7e635557-629e-448b-a48f-57a3f44737b8">


### Scaredy Cat:
<img width="1690" alt="BT_Scaredy" src="https://github.com/user-attachments/assets/3edb761d-7cc9-4e7e-ba16-94580754de3d">

## Screenshots:
![Purr_MainMenu](https://github.com/user-attachments/assets/0e40d75e-babc-4b0a-8996-2f5aba8555cb)
![Purr_Landscape](https://github.com/user-attachments/assets/63bb7308-d874-4681-9e05-e0ab5b6dea1a)
![Purr_Cats](https://github.com/user-attachments/assets/a0c628c9-823b-46b0-a33c-40fb971e392f)

## A team effort by:
![MAGGAM Logo White](https://github.com/user-attachments/assets/84b72adb-5c67-4e0d-8a41-f760b9624d4b)

