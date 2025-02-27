se-day-2-git-and-github

ANSWERS TO QUESTION 1
Version control is a system that tracks changes made to files over time, allowing users to revert to previous versions, collaborate on projects by merging changes, and maintain a clear history of modifications, essentially acting as a "time machine" for documents or code, especially in software development; key concepts include repositories, commits, branches, and merging, with the ability to work locally and then push changes to a central repository for sharing with others
Developers use GitHub to work together on a single project with the benefit of version control. This helps them reduce duplicating work. Plus, GitHub allows developers to try new things. If the changes aren't positive, they can easily revert back to the previous version.
Version control helps maintain project integrity by keeping a detailed record of all changes made to project files, allowing teams to easily track who made modifications, when they were made, and the ability to revert to previous versions if necessary, effectively preventing data loss and ensuring consistency across the project throughout its development lifecycle. 

ANSWERS TO QUESTION 2
Create a repository
•	In the upper-right corner of any page, select , then click New repository.
•	Type a short, memorable name for your repository. ...
•	Optionally, add a description of your repository. ...
•	Choose a repository visibility. ...
•	Select Initialize this repository with a README.
•	Click Create repository.
When creating a repository, key decisions include: choosing the right repository platform based on your needs, defining the repository's structure and file organization, deciding on access levels for collaborators, setting clear naming conventions, writing comprehensive documentation, and determining the level of public visibility for your repository; all while considering factors like project size, collaboration requirements, and version control system preference. 
Key points to consider:
•	Platform selection:
•	Which platform best suits your project type (e.g., GitHub for open-source, private repositories on a company platform)? 
•	Do you need advanced features like issue tracking, code review tools, or branching strategies? 
•	Repository structure:
•	How to organize files and folders within the repository for clarity and easy navigation 
•	Should you use a standardized directory structure for consistency across projects? 
•	Access control:
•	Who should have read-only access, write access, or administrative control? 
•	How will you manage user permissions for new team members? 
•	Naming conventions:
•	Establish clear and consistent naming standards for files, folders, and branches to avoid confusion 
•	Documentation:
•	Creating a comprehensive README file explaining the project purpose, usage instructions, and contribution guidelines 
•	Visibility settings:
•	Should the repository be public, private, or have a specific visibility level depending on the project's nature? 
•	Version control system:
•	Which version control system (like Git) aligns best with your team's workflow and preferred practices 


ANSWER TO QUESTION 3

A README file in a GitHub repository is crucial as it acts as the primary point of information for a project, providing a concise overview of what the project does, how to use it, and how to contribute, essentially serving as a "welcome mat" for anyone exploring the repository, whether they are potential users, collaborators, or new team members; this helps to streamline onboarding, encourage community engagement, and minimize confusion about the project's purpose and functionality

1.	Choose a Descriptive and Concise Title. ...
2.	Example: Bad: "MyApp" ...
3.	Provide a Brief Overview of the Project. ...
4.	Example: ...
5.	Improve Navigation for Large READMEs. ...
6.	List all Sections with Appropriate Links. ...
7.	Example: ## Table of Contents. ...
8.	List Prerequisites and System Requirements.


ANSWER TO QUESTION 4

A public repository on GitHub is accessible to anyone on the internet, while a private repository is only visible to the owner and those explicitly granted access by them, allowing for controlled collaboration and protection of sensitive code or information; essentially, the key difference lies in the visibility level of the repository. 

Advantages of a Public Repository:
•	Community Collaboration:
Anyone can view, fork, and contribute to your code, fostering wider collaboration and potential for improvements. 
•	Transparency and Open Source:
Ideal for open-source projects where sharing code is the primary goal. 
•	Code Review and Feedback:
Public repositories can readily receive feedback and suggestions from the wider developer community. 
•	Visibility and Recognition:
Can increase your visibility as a developer by showcasing your projects publicly. 
Disadvantages of a Public Repository:
•	Security Concerns:
Sensitive information like API keys or passwords can be exposed if accidentally committed to the code. 
•	Proprietary Code Protection:
Not suitable for projects containing confidential or proprietary code that needs to be protected. 
•	Potential for Code Issues:
Public repositories may attract pull requests with low quality or irrelevant changes. 
Advantages of a Private Repository:
•	Data Security: Protects sensitive information by restricting access to only authorized users.
•	Control Over Access: You can carefully manage who can view and modify the code within the repository.
•	Internal Project Collaboration: Ideal for team projects where code needs to be kept within the company. 
Disadvantages of a Private Repository:
•	Limited Collaboration:
Community feedback and contributions are restricted as only invited collaborators can access the code. 
•	Cost Implications:
Depending on your GitHub plan, private repositories may incur additional costs. 
•	Less Visibility:
Your project may not gain as much exposure or recognition compared to a public repository



ANSWER TO QUESTION 5
You can follow these steps for doing initial commit.
1.	Clone the empty repo. ...
2.	Now go to your repo using cd command and create a local branch say developement using command git checkout -b development.
3.	We can now add some files in the repo echo "A new repo" > Readme.
4.	Stage all the unstages files to commit git add .

Commits ensure that all changes are gathered in a central repository, keeping the entire team informed about the changes. Version Control: Commits are used to manage different versions of the software. This is especially important in large projects where tracking different versions and updates is done through commits.
