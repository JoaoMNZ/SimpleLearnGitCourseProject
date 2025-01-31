# SimpleLearnGitCourseProject

This course was about GIT basics and the final work was a project. The project is the implementation of a graph representation of a git repository:

![image](https://github.com/user-attachments/assets/9d4b8b20-2b09-49c4-80da-fc044bbc2a17)

My interpretation of this graph is as follows: The Integration Branch handles new features, using separate branches for development. When these feature branches complete their tasks, the Integration Branch performs a merge or rebase with them. After this, the HotFix Branch merges with the Integration Branch and then addresses any bugs in the code. Once the code is error-free, I merge it into the Production Branch. All new features or updates to the code will follow these same steps.
