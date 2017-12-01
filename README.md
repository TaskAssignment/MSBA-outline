# MSBA: Multi-source Bug-assignment
All the MSBA experiment requirements (data set, code, etc.) are available here.
The data set for 13 popular Github projects including:
- 7,438 developers
- 64,474 bug reports
- 93,016 bug-assignments
- 281,336 commits
- 80,803 pull requests
- 351,940 bug comments
- 30,155 commit comments
- 298,579 pull request comments

In addition, there is another data set for multi-project experiment (using evidence of expertise from sub-projects to assign bugs in the parent project) including two popular projects (angular/angular.js and rails/rails) and their 6 and 13 sub-projects:
- 2,574 developers (as sub-project members)
- 11,952 bug reports
- 17,426 bug-assignments
- 17,352 commits
- 5,740 pull requests
- 50,437comments
- 1,712 commit comments
- 16,414 pull request comments

Here's the data model of our experiments:
![Alt text](/Schema.png?raw=true "The data model")


Our bug assignment Java **code**, the **data set** (which is also used as input of our code), **output** and **documentations** can be accessed from: 

- **https://github.com/TaskAssignment/MSBA**
(This is a private repository and you need access to see the repository, otherwise you will get a "404" error)

If you need asccess to the repository, please contact alisajedi@ualberta.ca stating your name and affiliation.

We made huge effort to gather and clean this data set and politely ask the users of this data set the followings:
- Do not change or redistribute this data set without our consent.
- Do not use it for commercial purposes and applications.
- Please acknowledge / cite our work as the origin of the data set (please ask alisajedi@ualberta.ca for citation details).
