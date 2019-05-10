## Using the Command Line

Below I will be discussing how to clone a repository on your MacOS computer, edit it, and push the file back into your new GitHub repository. 

#### Step 1
First we must clone the repository URL to our local system (Terminal). This can be down by clicking the green "Clone or download" drop down menu and clicking on the notebook icon as shown:

<img width="1071" alt="Screen Shot 2019-05-09 at 6 35 14 PM" src="https://user-images.githubusercontent.com/42652935/57493237-b8525400-7289-11e9-9945-4ccc30652c6c.png">

#### Step 2
Next, we need to clone the GitHub repository you have created to our local computer. Here we will be using the git command "git clone". This command creates a new directory and has remote-tracking ability in the cloned repository. For the sake of this tutorial, I have cloned my "Hello-World" repo to my desktop as shown below:

"cd" is a terminal command that allows me to open up my desktop file on my Mac to allow for the repo to be cloned to. 


<img width="565" alt="Screen Shot 2019-05-09 at 6 43 13 PM" src="https://user-images.githubusercontent.com/42652935/57493525-dc626500-728a-11e9-9c4f-e04441de5cfc.png">

Hello-World folder shows up in my desktop and is available to be edited. 

#### Step 3
To be edited, I converted the Hello-World file into a text editor. I added a little note to show a before and after in the "Hello-World" repository I created.

<img width="636" alt="Screen Shot 2019-05-09 at 7 01 30 PM" src="https://user-images.githubusercontent.com/42652935/57494714-3b76a880-7290-11e9-89a6-ba95a7396d66.png">

#### Step 4 
Below I will perform the git command "git status". I have edited the README.md file at this point. Terminal knows that the file has been modified but not yet added back to the README.md file stored on Desktop. (Hence the red text)

<img width="537" alt="Screen Shot 2019-05-09 at 7 20 31 PM" src="https://user-images.githubusercontent.com/42652935/57494715-3dd90280-7290-11e9-89bb-5e7d556fbea8.png">

#### Step 5
At this point the file has been edited, but needs to be staged for a commit to be cloned back into our GitHub repositories. To perform a push we will use the git command "git add" with the "READ.md" file following (shown below). Now, when we check the status of our file modifications, you can tell it is staged and ready for a commit. (green text)








[< Previous](Repository.md)

[Back to Home Page](README.md)
