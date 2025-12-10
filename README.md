# grannypanic

## Grannypanic!

## Description
This game project was done as part of ICT-engineering degree during autumn 2025. The idea was to create a game with physics as realistic as possible. 

We ended up with an idea, where a sweet granny has to make her way to the store as fast as possible using a wheelchair. The 'realistic physics' -part was executed by us building the controller directly into a real wheelchair. We used two ESP32 for the controllers on each side of the wheels (please refer to the folder "SUUNNITTELU" for images of the final version of the wheelchair setup). The movement of the wheels is tracked by two magnetic Hall sensors (1GT101DC), one on each side of the wheels. In addition to this we 3D-printed a wheel with embedded holes for 8mm magnets and the movement was tracked by the change in magnetic force by the magnets passing. Blender model of the magnetic wheel can also be found from the "SUUNNITTELU" -folder.

This repository is mainly done to showcase the project as a whole, the codes aren't optimized and the final version of the game is far from "perfect". PLEASE NOTE THAT THIS GAME WAS DONE WITH UNITY VERSION 6000.2.2f1.

## Visuals
![Description](Traileri/visuals1.gif)
![Description](Traileri/visuals2.gif)

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
