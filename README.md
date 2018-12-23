# azure-devops

Three main areas: 
- Source control (software versioning)
- Tracking tools (planning)
- DevOps tools (build, test & release)


## Source control: 
Git (distributed) and TFVC (centralized). Biggest difference:
With Git, each developer has a *local copy* of the code on their machine including *all branch and history information*. The developer works directly with their **own local** repository. To compare the history of a file, with GIT you don't need to contact the server.

With TFVC, a developer has only *one version* of each file on their machine. To compare the history of a file, with TFVC, you need to contact the *server*. Branches are path based and created on the server. [Source](https://docs.microsoft.com/de-de/azure/devops/user-guide/concepts?view=vsts#source-control)
