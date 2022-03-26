# Hack-o-Protoquest
Hack-o-protoquest is a platform that allows students to turn their ideas into reality while also supporting society with their useful solutions through the development of real-time projects.

More information at [HACK-O-PROTOQUEST](https://www.gdscsrcasw.live/hack-o-protoquest/)

## How To Use
To submit your prototype through your repo on GitHub, you'll need [Git](https://git-scm.com/) and Latest Version of any web browser installed on your computer.
Follow all the steps carefully to get your submission COUNT!

      # Fork this repo using FORK button on top-right
      
      # Go to the forked repo
      
      # Click on the CODE button and Copy the https link
      
      # Open Git Bash
      1. Change directory to the desired location
      2. clone the repo using command:
      $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
      
      # Create a branch with the name of your TEAM
      
      # Add all files and then commit.
      
      # Push the changes into the branch.
      

## Contribute

### Step 1: Fork this repository.
   ![Fork button](https://github.com/MBtions/New/blob/master/fork.png?raw=true)

### Step 2: Go to your repository.
Your repository will look like this: **{your-username}/Hack-o-Protoquest**
   ![your repository](https://github.com/MBtions/New/blob/master/your-repository.png?raw=true)
   
### Step 3: Copy the link to YOUR repo.
Now, on your repo page, click the CODE button and copy the https link.
   ![Click on Code button and copy https link to your repo](https://github.com/MBtions/New/blob/master/click%20on%20code%20and%20copy%20the%20link%20to%20your%20repo.png?raw=true)

### Step 4: Open Git Bash.
Change the current working directory to the location where you want the cloned directory.

### Step 5: Type `git clone`, and then paste the URL you copied earlier.
`$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`

### Step 6: Press Enter to create your local clone.
```
$ git clone https://github.com/MBtions/Hack-o-Protoquest.git
Cloning into 'Hack-o-Protoquest'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

### Step 7: Go to the Folder
      `$ cd Hack-o-Protoquest`

Then, check the status using git status  
```
$ git status  
On branch main  
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean  
```
There is nothing to commit now as there are no changes done by you.

### Step 8: Create a branch with your TEAM-NAME
Create a new brach with team name (say, Team: Power_Codhers) using command $ git checkout -b {branch-name}
```
$ git checkout -b Power_Codhers
Switched to a new branch 'Power_Codhers'
```

### Step 9: Add files (PROTOTYPE & Power Point Presentation) in the cloned folder.
Add the prototype file and PPT into the folder cloned.  
Check the status of your repo after adding all required files.
```
$ git status
On branch Power_Codhers
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        [PRESENTATION] CoVShorts.pptx
        [PROTOTYPE] CovShorts_News_Article_Text_Summariser_App.ipynb

nothing added to commit but untracked files present (use "git add" to track)
```
![Added files in the status](https://github.com/MBtions/New/blob/master/added%20files-%20prototype%20and%20presentation.png?raw=true)
```
$ git add .
$ git commit -m "Added prototype and Presentation"
[Power_Codhers dad4918] Added prototype and Presentation
 2 files changed, 539 insertions(+)
 create mode 100644 [PRESENTATION] CoVShorts.pptx
 create mode 100644 [PROTOTYPE] CovShorts_News_Article_Text_Summariser_App.ipynb
```
After adding all the changes, PUSH the branch to remote repository using git push -u origin {branch-name}
```
$ git push -u origin Power_Codhers
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'Power_Codhers' on GitHub by visiting:
remote:      https://github.com/MBtions/Hack-o-Protoquest/pull/new/Power_Codhers
remote:
To https://github.com/MBtions/Hack-o-Protoquest.git
 * [new branch]      Power_Codhers -> Power_Codhers
Branch 'Power_Codhers' set up to track remote branch 'Power_Codhers' from 'origin'.
```
![Push Changes on remote repo](https://github.com/MBtions/New/blob/master/push%20changes%20on%20your%20remote%20repo.png?raw=true)

### Step 10: Create Pull Request






