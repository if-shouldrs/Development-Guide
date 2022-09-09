# Introduction
This repository guides you through every relevant step and aspect of developing a project, so that even without your morning coffee or after months of development hiatus, you can click through the different sections of this document and remember everything you're supposed to do to achieve good results cleanly and efficiently.

# Development Stages
Every development project is broken down into the following categories:

## Planning
Figuring out how to tackle a project involves asking these crucial questions:
 1. [What does the end result look like](What%20does%20the%20end%20result%20look%20like.md)?
 2. [What are the bare minimum features required](What%20are%20the%20bare%20minimum%20features%20required.md)?
 3. Technologies and Functionalities:
	 1. [What technologies should you use](What%20technologies%20should%20you%20use.md)?
	 2. [What functionalities do you need to complete the project](What%20functionalities%20do%20you%20need%20to%20complete%20the%20project.md)?
 4. [On which sprint do you do what](On%20which%20sprint%20do%20you%20do%20what.md)?

If you don't know how much time to spend on each Scrum activity, see [here](Scrum%20Durations.md).

If you're developing your own project, and specially if it's on a smaller scale than 1 month, look at [Applying Scrum methodologies at a lower scale](Applying%20Scrum%20methodologies%20at%20a%20lower%20scale.md) too.

## Development
Ideally you're so used to developing that everything comes naturally, but realistically there'll always be a lot to keep track of and the process may differ per project.

Here's everything you have to pay attention to while developing something:
 1. Write tests first, code later (TDD) - [Writing tests](Writing%20tests.md);
 2. Write comments everywhere. Make sure you can explain your code;
 3. Review the [SOLID](SOLID.md) principles;
 4. Review the [Top 10 OWASP Security Concerns](Top%2010%20OWASP%20Security%20Concerns.md) before and after adding features;
 5. Think like the end user - don't waste time on functionalities they don't want;
 6. Create [pipelines](Deployment%20Environments.md#Pipelines) to ensure nothing breaks and deployment is easy;
 7. Write documentation per story completion and not per sprint;

When it comes to UI design specifically, you should:
 - Review the [W3C Accessibility Guidelines](W3C%20Accessibility%20Guidelines.md);
 - Review [Usability Guidelines](Usability%20Guidelines.md);

TODO: Delivery and Operation sections
