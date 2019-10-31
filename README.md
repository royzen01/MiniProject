# MiniProject

First Name | Last Name
------------ | -------------
Roy          | Sanchez 
Hayk         | Samvelyan
---
### Tasks to complete:
- [x] Roy - 10 tasks
- [ ] Hayk - 10 tasks
- [ ] Answer first section
- [x] Answer second section (workflow)

---

### Section 1 definitions

<dl>
  <dt>cd</dt>
  <dd>cd is a Terminal/Command Line command used to switch between folders in a directory</dd>

  <dd> <b> cd foldername </b> goes to a particular folder name </dd>
  
  <dt>mkdir</dt>
  <dd>mkdir makes a new folder in your designated directory</dd>

  <dd> <b> mkdir foldername </b> makes a particular folder name </dd>
  
  <dt>cp</dt>
  <dd>cp copies files and directories in the file system</dd>

  <dd> <b> cp filename </b> copies selected file </dd>
  
  <dt>pwd</dt>
  <dd>pwd stands for Print Working Directory which displays the full address of the current directory you're in. It helps you find where you are in the system</dd>

  <dd> <b> pwd </b> prints your current path starting with the root </dd>
  
   <dt>mv</dt>
  <dd>mv lets you move or rename files within the file system</dd>

  <dd> <b> mv [filename] [directory] </b> moves selected file to desired directory </dd>
  <dd> <b> mv [filename] [newfilename] </b> renames desired file </dd>
  
  <dt>rm</dt>
  <dd>rm removes files and directories in the file system</dd>

  <dd> <b> rm [filename] </b> removes selected file name </dd>
  <dd> <b> rm -d [directory] </b> removes an empty directory </dd>
  
  <dt>history</dt>
  <dd>history allows to you to review all previously inputted commands from the start of the current session</dd>

  <dd> <b> history </b> displays a list of all previous commands </dd>
  
</dl>  

### Section 2 definitions

<dl>
  <dt>GitFlow</dt>
  <dd>GitFlow is the structure by Git which operates. The idea behind it is to have multiple paths,
  or branches, which can be developed independently from the master branch. This allows the 
  development of new features and fixes to be developed without interferring with the master branch.
  Once the features or fixes are ready to go they can be merged back into the master branch which
  promotes seamless collaboration.</dd>
  
  <dt>Repository</dt>
  <dd>A repository, also reffered to as "repo", is a directory that houses one of your projects.
  Here is where you will store your code, text files, images and other data. A repo can live 
  localy on your computer or it can be on a remote host like GitHub.</dd>
  
  <dd> <b> git init </b> initializes a repository </dd>
  
  <dt>Clone</dt>
  <dd>Git clone is a command used to copy an existing repository onto a target local repository. One way
  this can be helpful is if you find a remote repository and wish to copy parts of it into your own.</dd>
  
  <dd> <b> git clone repository_url  </b> copies the targeted repository into your current one </dd>
  
  <dt>Fork</dt>
  <dd>A fork is a copy of a repository. Forking is useful for collaborating with others because
  they can make changes to your project without affecting it directly.</dd>
  
  <dt>Branch</dt>
  <dd>Git allows one to branch-off from the main project in order to work on a feature or fix without getting
  in the way of the main project. It allows one to make changes without disrupting the master branch 
  and and thus avoiding conflict issues.</dd>
  
  <dt>Commit</dt>
  <dd>This command captures a snapshot of the current changes made to the project. This indicates that your
  changes are working and you are ready to apply them to the project.</dd>
  
  <dd> <b> git commit -m ' ' </b> Lets you commit your currently staged files. the -m flag lets you set a 
  comment between the single quotes </dd>
  
  <dt>Merge</dt>
  <dd>Git merge is applied in two different scenarios, but works the same in both. First would be if you are
  working on a seperate branch, git merge branchname will allow you to merge the named branch to the master.
  The other situation in which merge is used is when performing a git fetch. Git fetch copies down the changes
  added to the remote repository onto your local one, and git merge then applies those changes to your files.</dd>

  <dd> <b> git merge branchname </b> merges the named branch to the master branch</dd>
  <dd> <b> git merge </b> while in your local repo applies the changes grabbed after a git fetch</dd>
  
  <dt>Checkout</dt>
  <dd>The git checkout has many uses. One of its main uses is to switch between the branch you currently want
  to work on. Another popular property of it is that it has the ability to restore files back to a specific commit.</dd>

  <dd> <b> git checkout branchname </b> will put you in the targeted branch if it exists</dd>
  <dd> <b> git commit_id </b> will copy a specific commit</dd>
  
  <dt>Push</dt>
  <dd>Git push is how you send commits from your local repository over to the remote repo.</dd>

  <dd> <b> git push origin branchname </b> pushes your commits to the remote repository and named branch</dd>
  
  <dt>Pull</dt>
  <dd>Git pull incorporates the changes from a remote repo onto your designated local repo. Git pull 
  works as a combination of git fetch and git merge</dd>

  <dd> <b> git pull remote_repo_name </b> downloads and immediately applies the latest changes of the target repo </dd>
  
  <dt>Remote</dt>
  <dd>Git remote is a command used to interact with remote repositories. It can establish and remove connections</dd>

  <dd> <b> git remote add <name> <url> </b> sets up a connection to a remote repository and give it a name </dd>
  <dd> <b> git remote rm <name> </b> removes the connection to the named repository </dd>
  <dd> <b> git remote show </b> will give details on the configuration of the remote repository </dd>
  
  <dt>Status</dt>
  <dd>Git status gives you information of your current repository. It lets you know if changes have been made
  and if any have been staged for commit.</dd>

  <dd> <b> git status </b> prints information on your current directory</dd>
  
  <dt>Master Branch</dt>
  <dd>The master branch is your first and usually last branch of your project. It is your main branch where everything
  will come together ultimately. Feature branches are created with the intention of ultimately being merged backed into
  the master branch.</dd>

  <dd> <b> git checkout master </b> will put you in the master branch if you have switched out</dd>
  
</dl>


http://www.github.com/ 

![GitHub Logo](/images/giticon.png)

> IS 117 - Fall '19 - Keith Williams

:grinning: :smile: :heart_eyes: :stuck_out_tongue: :cowboy_hat_face:
