# Git Commands and Terminology <a name="top">

*	<a href="#repository">Repository </a>
* <a href="#clone">Clone</a> 
*	<a href="#clone">Fork </a> 
*	 <a href="#clone">Branch</a> 
*	 <a href="#clone">Commit</a> 
*	 <a href="#clone">Merge</a> 
*	 <a href="#clone">Checkout</a> 
*	 <a href="#clone">Push</a> 
*	<a href="#clone">Pull </a> 
*	 <a href="#clone">Remote Add / Remove / Show </a> 
*	 <a href="#clone">Status</a> 
*	<a href="#clone">Master Branch </a> 

___________________________________________________________________________________________________________________________________
</br>
<a name="repository">
<b>Repository</b>
  
A repository generically refers to a central place where data is stored and maintained. A repository can be a place where multiple databases or files are located for distribution over a network, or a repository can be a location that is directly accessible to the user without having to travel across a network. 

Git is a program that tracks changes made to files. Once installed, Git can be initialized on a project to create a Git
repository. A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your
project, building a history over time.

![](git_repos_image_source.png)


To start a new git repository using the command line:
1.	Create a directory to contain the project.
2.	Go into the new directory.
3.	Type git init .  -->To initialize the directory and creates a new Git repository
4.	Write some code.
5.	Type git add to add the files.
6.	Type git commit .

</a>

<a href="#top">Return to  Git Commands and Terminology</a>
<br>
<br>

<a name="clone"> 
<b>Clone</b>

The git clone command copies an existing Git repository. This is sort of like SVN checkout, except the “working copy” is a full-fledged Git repository—it has its own history, manages its own files, and is a completely isolated environment from the original repository. 
The "clone" command downloads an existing Git repository [remote] to your local computer.
You will then have a full-blown, local version of that Git repo and can start working on the project.
Typically, the "original" repository is located on a remote server, often from a service like GitHub, Bitbucket, or GitLab). That remote repository's URL is then later referred to as the "origin".

![](clone_image.png)

Example: <br>
Thie following command will download the project to a folder named after the Git repository ("Mini_Project_1" in this case) <br>
Repository Owner USERNAME: Web_Dev_IS601   <br>
GITHUB REPOSITORY PROJECT: Mini_Project_1 <br>
cd folder/to/clone-into/        ---> Change to the folder on your local directory that will contain the cloned repository <br>
Clone Command**: <br>
<b>git clone </b>[https://github.com/Web_Dev_IS601/Mini_Project_1.git]  <br><br>
**SSH/HTTPS URL FORMAT :   git@name-of-git-host:username/project-name (SSH version) or [https://name-of-git-host/username/project-name] (HTTPS version).


</a>
<a href="#top">Return to  Git Commands and Terminology</a>
