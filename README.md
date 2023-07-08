# Github-branching-strategy
A project on git ( a version control system ) explaining the best possible branching strategy for any team to adopt for their softwares.


![gitmodel](https://github.com/Pushkar-sharma28/Git-flow-branching-strategy/assets/108188779/f172c40f-1a64-4d68-858c-959d727af86f)



- **Master branch**: This branch handles production deployments.

- **Feature branch**: This branch is used for developing new features during a sprint (it will be merged with the main branch once the feature is successfully implemented).

- **Release branch**: This branch is used for higher environments (QA/STAGE), where the code is tested but not used in production.

- **Develop branch**: This branch manages the changes made by developers in their own branches.

- **Hotfix branch**: This branch addresses production-related issues, such as bug fixes after a release. It is used for resolving such issues.



### KUBERNETES BRANCHING STRATEGY 

its a big project which handles thousands of open source contributors and different versions of the application as well.


kubernetes branching strategy : 

![Screenshot (62)](https://github.com/Pushkar-sharma28/Git-flow-branching-strategy/assets/108188779/bf5b7d87-2a14-4785-a9e8-680fe6d3df1c)


- the idea is for any new feature there will be a new branch which will be merged into the main branch after full testing and will be release as a minor version update once its is done the branch will be saved as the release branch , here the development branch are the open source contributor which will be merged through pull request.
