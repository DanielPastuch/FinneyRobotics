# FinneyRobotics
Code for Finney Robotics Team

<h2>Steps for pulling the GitHub code into Eclipse</h2>
- Create a new project by right clicking in the Package Explorer and selecting New > Project > Robot Java Project
- Give the project a name and select "Iterative Robot"
- Open the GIT Perspective by clicking window > Perspective > Open Perspective > Other and select Git
- Click the Link "Clone a Git Repository"
- Paste in the Git URI and hit next
- only select the desired branch and hit next
- Create a new directory to put the Git workspace in and remember the directory
- Finish saving that git repository
- Right click on your previously created Eclipse Project and select Import > File System
- Browse to your previously created GIT repository
- Click Finish
- When it is overwriting files DO NOT click "Yes to all"
- Instead click "No" when asked to replace the .project file and "Yes" to all the rest
- You should now have all of the source code in the project
- You should also now be able to right click on the project > Run As > WPILib Java Desploy
