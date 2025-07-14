 # Git-Github
What did I learned in this GIt &amp; Github Journey ???

# Git :- #

This is an incredible journey as in this journey I learnt how to create check points and how to commit changes and how to and track and untrack changes i learn how to roll back and also made that in practical world this increases my confidence completeland still many other things left to work on but this "GIT Journey is amazing it made me understand how important the check point is and how the necessasity of roll back feature help to save the coode "

1. I firstly learned to configure and install it then add extension
2. so first of all downlaod as you downlaod from the website for specific system like mac, linux and windows
3. now open VScode and open the extension tab and then download gitblame and then its time to install the extension after installing
4. Configure the git by using CMD  open that and type specific commands that is
{ 1. git config --global user.name "Your name"
  2. git config --global user.email "youremail@gmail.com"}

Now there are 3 stages in this Git 
1->Untracked (Git knows there is a file but it does take care of that file git usually dont care )
2->Added or staged (now git have the permission to create save points and maintain the files)
3->Commited (Git had created the check point based on the recent changes)

# FEW BASIC COMMANDS OF GIT #
1. git log --oneline  or git log --graph (This tell how many commits have you done so called it take the history)
2. .gitignore (Open this file and type any file name which you dont want to track the git will ignore it)
3. git reset --hard Head~1 (in this command you can roll back to the previus version the number by tweaking the number in front of HEAD )
4. git stats -s (we can check that in which stage we are like tracked , untracked , commited)
5.                                               From Here we are going to learn about branch
6. git branch "branch name" (this is used to create branch and this also states the best practice to create branch before working on the main branch
7. git switch "branch name" (using this command we can switch between the branches weather the main or any other branch)
8. git merge "branch name "  (to add the branch code to the main file)
9. git branch -d "branch name " (this commands delete the branch and its existence and its files )

# Github :- #

This this one most usefull thing i have ever learned as this teaches me how to collaborate with othere developer and manage the code database like this is the central codebase from here we can easily maintain the version control of the code and anyone can easily fetch and pull and push with the great ease of work in this Github journey I learned :-

1. echo "#MessageToBeWritten" >>readme (in this an readme file is created based on the message you have set to written inside the file )
2. git init (This usualy initialize the directory that whatever the operation is going to be perfomed is from this specific directory only)
3. git add . (This command helps to add all the files or in other words we can say it stages the files for the further commit )
4. git commit -m "Message" (In this command the files are commited or in other words we created an checkpoint )
5. git branch -M main (This command specify that the user wants to make the changes or the changes should reflect in main branch)
6. git remote add origin https://github.com/404xSumit/"repo name accordingly" (this command specify and give an specific path to the system that from now onwards my every changes should be posted in this repository)
7. git push -u origin main (this commands upload the files to the github and then we can see our all files get uploaded in the github repositoory)

# From here onwards let me explain the process of the collaboration and what to do after collaboration  #

1. To collaborate with the the others in your project or in repository
  1.1. You just need to go to the setting of you repo and there you see the collaboration tab there you just add the name of the person whom you wanted to collab once   done sent the invitation after accepting the invitation
2.One should clone the repo locally and create the branch before working on it
3. git clone https://github.com/404xsumit(username)/XYZ(repository name) [this is going to create a local directory of that repo and you can add thing after making branch]
4. git switch -C "Branch_name you want" (This is going to create the branch name and before doing anything it is mandatory to create a branch othervise the central codebase is altered )
5. once done with your editing you can add, commit , push into your branch
6. git add . (after completeing you edit with code)
7. git commit -m "Type message or inform about what did hyou have changed " (this will create a checkpoint for you and saves the code with giving a description)
8. git push -u origin "branch name " (this command pushes you code to the github in your own branch where leader can merge the code )
9. After performing these steps inform your leader that you have pushed the code in your branch and tell him to merge the code

# Once Done the leader have to pull the code from the branch and add the code to merge to the central code base  #

1.The leader have to perform the user have to fetch the code from the branch and check if everything is written accordingly and once checked the user need to fetch your branch then switch to main branch then merge then push to github
2.git fetch (this command is used to fetch the branch and the code written over there basically each and every changes )
3.git switch "the pesons branch name " (this command is used to switch from the main branch of your compter to the fetched branch for checking the code or the content written there is valid or not)
4.git switch main (this command is use to switch from that branch to the branch for merging the code with main code)
5.git merge "branch name" (this is used to merge the branch with the main branch or make the code merge with the branch code with the main code )
6.git push -u origin main (And here we pushed the command to the main directory or uploade the central code base with code)

# Now the central code base is upgraded no the thing is that the person's code base should also be updated so for that they also have to fetch and pull the code from the repo and make the branch again or work on the previous branch they made #

1.git fetch (This is again used to fetch the code base based on the main branch code)
2.git pull (this fetch the things from the central code base and merge the code which was previously in main code)

# [ This is the complete process of Git && Github I enjoyed learning and will use this on daily basis uploading other code to my Github Repo ] #






















