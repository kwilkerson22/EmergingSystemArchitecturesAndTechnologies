# EmergingSystemArchitecturesAndTechnologies

**Summarize the project and what problem it was solving.**

I developed a smart thermostat using an AHT2 temperature sensor (I2C), two status LEDs to indicate heating and cooling via GPIO fade-in/out, and three buttons to toggle system states (off/heating/cooling) and adjust the set temperature using GPIO interrupts. The system displayed real-time date, time, room temperature, and set temperature on an LCD, and ouput data over UART. The prototype provided a foundation for future networked versions of the product.

**What did you do particularly well?**

I did well with troubleshooting and testing to ensure that the system aligned with the business requirements. I validated each feature from temperature sensing to output display to confirm correct behavior under different conditions. I also maintained clear, modular code with well-documented functions, which improved readability and made debugging and testing more efficient. This approach helped in identifying and resolving issues quickly. 

**Where could you improve?**

I could improve on adding more detail to my state machine diagrams, particularly by clearly documenting the conditions or events that trigger transitions between states (e.g., button presses, temperature thresholds). While the functionality was implemented correctly, a more thorough visual representation would have improved design clarity. I will strive to improve on this in future projects.

**What tools and/or resources are you adding to your support network?**

I plan to incorporate more documentation websites and technical resources into my workflow to gain a deeper understanding of how functions, applications, and systems work. Utilizing official datasheets, developer forums, and comprehensive tutorials will help me troubleshoot more effectively and expand my learning in future projects.

**What skills from this project will be particularly transferable to other projects and/or course work?**

I improved my troubleshooting skills, especially in resolving issues that arise when connecting hardware with software. This was my first course involving such integration. Additionally, I improved my ability to write efficient code, which is crucial for conserving limited resources in embedded systems. These skills will be valuable in future projects and coursework involving hardware interfaces, real-time systems, and resource-constrained environments.

**How did you make this project maintainable, readable, and adaptable?**

The code from this project was designed with modularity and clarity by using descriptive function names, consistent formatting, and comments to explain system logic.
