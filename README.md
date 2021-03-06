# First-Contribution

It's always hard to start something new as a beginner, but at one point of time, everyone is a beginner.
This project is created to help those novice people who are enthusiastic in making their contribution in open source project.
So if you are the one, follow the below steps:

## How to make changes to the project
# 1. Fork this Repository.
To edit or commit changes to a project which you like, you need to fork that<br>
Forking is a process where the master repository will be created in your github profile.<br>
You can find the fork option here<br>
<img src="https://i.imgur.com/W10USEV.png">

# 2. Clone the repository.
After forking, if you are willing to commit small text changes, then github edit is preferrable.<br>
If you want commit major changes or change the source code<br>
To do that, you need to clone the repository created on your profile locally.<br>
Here you can find the clone option<br>
<img src="https://i.imgur.com/Eoijt1u.png"><br>
Copy the link, open github CLI or any of your preferred CLI,<br>
Then type git clone ***link***

# 3. Create a branch.
This statement is self explanatory<br>
To create a branch locally, follow the following steps<br>
$ git checkout master (change to master branch)<br>
$ git checkout -b dev master (create a branch called dev from master)<br>
$ git checout dev (switch to dev branch) <br>
$ git checkout -b branch1 dev (create a branch called branch1 from dev branch)<br>
You can name it anything you want or the suggested one by the master<br>

# 4. Make necessary changes and commit those changes.

Make the necessary changes you are willing to and save them.<br>

# 5. Push those changes into github.

After making the necessary changes, you need to push them to the repository, using git commands<br>
You can check the following commands,<br>
$ git init
$ git add .
$ git commit -m "first commit"
$ git remote add origin ***link***
$ git push -u origin master

# 6. Create pull request.

All set, now you need to create a pull request to merge the changes you have made with the master branch<br>
You can follow this image for the guidelines to create a pull request<br>
<img src="https://i.imgur.com/J4BwPld.png"><br>
