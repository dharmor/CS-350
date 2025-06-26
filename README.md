# CS-350

# Summarize the project and what problem it was solving.

The project was designed to produce a smart thermostat and send the data to a server. The sensor used captured the temperature and humidity and allowed for a set point at which the cooling or heater would be turned on if the values were above or below, respectively. 

# What did you do particularly well?

The project was designed to produce a smart thermostat and send that data to a server. In its operation, when the temperature is above or below the set point, the cooling or heating system would be turned on, depending on the value.

# Where could you improve?

An improvement would be to fix the response when the buttons are pressed. In its present state, it runs in a separate thread and is activated by an interrupt. When I was testing the thermostat and pressing the buttons, at times the button wouldn’t respond or it would register twice. For example, if the set point was at 72 degrees and you select to increase the set point, it may jump to 74 instead of 73 degrees

# What tools and/or resources are you adding to your support network?’

One of the tools I’ll be adding to my library is the Python State Machine library. I found it helpful and would solve some issues I’ve had in the past with designing a system.

# What skills from this project will be particularly transferable to other projects and/or course work?

The primary skill set from this project is interfacing code with physical objects. Usually in courses you are just programing code with no interface to the real world.

# How did you make this project maintainable, readable, and adaptable?

Maintainable:
In order to make the codebase maintainable, I separated each feature or function into its own component or class, so that changes could be made without affecting unrelated parts.

Readable:
My coding practices include consistent naming conventions, logical structure, and breaking down large functions into smaller, single-purpose ones.
Adaptable:
Since each feature of the project was modular, it is easy to add or change features. For instance, the temperature and humidity component uses a class that can be changed to another version or a completely different component.
