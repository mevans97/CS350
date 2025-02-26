# CS350
Project 2

Project Summary
This project is a smart thermostat built with a small computer (Raspberry Pi) that automatically adjusts heating or cooling based on room temperature. It uses colored lights to show if it’s heating (red), cooling (blue), or off, and has buttons to change settings or adjust the target temperature. A screen displays the current time, temperature, and thermostat mode, aiming to keep a room comfortable while using energy efficiently.

What Was Done Well
The thermostat switches between modes smoothly, like a traffic light changing colors, and the screen updates without lag. Buttons respond instantly to adjust settings, and the code is organized in clear sections, making it easy to tweak or add features. The lights dim or brighten gradually when needed, giving a visual cue about how the system is working.

Areas for Improvement
The system could handle unexpected issues better, like if the temperature sensor disconnects. Some parts of the code use unclear numbers (e.g., "6" or "11") that could be named simply, like "display_time_interval." The temperature reading might also benefit from rounding instead of cutting off decimals for better accuracy.

Tools and Resources Learned
The project uses plug-and-play code tools to interact with buttons, sensors, and lights, which simplifies building gadgets. Skills like organizing code into modules or managing multiple tasks at once (like updating the screen while checking temperature) are handy for future tech projects. These tools and techniques are widely used in smart home devices or apps.

Transferable Skills
Breaking complex tasks into smaller, organized steps (like separating display updates from temperature checks) is useful for app development or problem-solving. Learning to design systems that can grow (e.g., adding new features) applies to many tech projects. Handling hardware components builds confidence in working with electronics or IoT devices.

Maintainability and Adaptability
The code is split into logical sections, like chapters in a book, so updating one part doesn’t break others. Clear names for functions (e.g., "update_lights") help anyone reading the code understand what each part does. The design allows easy additions, like connecting a humidity sensor or adding a timer, without rewriting everything from scratch.
