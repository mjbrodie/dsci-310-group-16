# Predicting Win Rate of Tennis Players
### Group Project Repository for DSCI 310 - Group 16

## Authors/Contributors:
* Ammar Bagharib  
* Miles Brodie  
* Sammy Gulipalli   

## Summary of Project
    (add in intro and motivations behind project)
    (add in summarised analysis)
    
## Important Project Rules and Regulations
- [Project Contributing Guide](https://github.com/mjbrodie/dsci-310-group-16/blob/main/CONTRIBUTING.md)
- [Code of Conduct](https://github.com/mjbrodie/dsci-310-group-16/blob/main/CODE_OF_CONDUCT.md)

## Detailed Analysis
The detailed analysis can be found [**here**](https://github.com/mjbrodie/dsci-310-group-16/blob/main/Analysis/Predicting_Win_Rate_of_Tennis_Players.ipynb)
    
## Dependencies required
The following are dependencies used within this project, and that which is necessary to reproduce an identical analysis.
| Package Name | Version |
| ------------ | ------- |
| R            | 4.1.3   |
| tidyverse    | 1.3.0   |
| tidymodels   | 0.1.1   |
| GGally       | 2.1.2   |
| remotes      | LATEST  |
| repr         | LATEST  |
| rvest        | LATEST  |
| stringr      | LATEST  |
| DBI          | LATEST  |
| dbplyr       | LATEST  |
   
   see [Dockerfile](Dockerfile)
   
## How to reproduce this project's Analysis. 
### Set Up Your Environment

- Sign up/ Log in a [Docker](https://hub.docker.com) account.

- Install Docker in your computer.

Fork this project's repository on GitHub and then clone the fork to your local machine. For more details on forking see the [GitHub
Documentation](https://help.github.com/en/articles/fork-a-repo). Type in the following command in your Terminal.
```
$ git clone https://github.com/mjbrodie/dsci-310-group-16
```
To keep your fork up to date with changes in this repo, you can use the fetch upstream button on GitHub. More details regarding fork syncing, e.g., syncing from your terminal instead of directly on Github can be found [**here**](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork). 

Then, fire up your Terminal on your local machine, and using Docker, follow these steps to reproduce this analysis:

**1. Pull down docker image**
Type in the following command in Terminal.
```
docker pull *(name of our docker project:latest)*
```
Up to the present, the latest version is v_____. Replace `latest` with another specific version accordingly.

**2. Run docker image**
To mount your current directory to a container from the docker image of this project, `cd` to the **root** of the cloned repo, then run the command:
```
docker run --rm -p 8888:8888 -v ${PWD}:file_path *(name of our docker project:latest)*
```
Navigate to the directory *file_path* where you mounted your files via: cd file_path and type `ls` to ensure you can see them.
   
## Licenses
- MIT license for project analysis (completed in a jupyter notebook)
