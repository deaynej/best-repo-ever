# best-repo-ever
Salesforce Trailhead Module: Git and GitHub Basics > Work with the GitHub Workflow
Git uses the config settings for your user name and email address to generate a unique fingerprint for each of the commits you create. 

You can't create commits without these settings, so set them yourself using your command line application:

git config --global user.name "First Last"
and then enter,

git config --global user.email "you@email.com"

CONFIGURE autocrlf
Next, we set core.autocrlf (autocrlf stands for auto carriage return line feed). Different systems handle line endings and line breaks differently. If you open a file created on another operating system and do not have this config option set, Git will think you made changes to the file based on the way your operating system handles the line endings.

For Windows users enter:

git config --global core.autocrlf true
For Mac or Linux users enter:

git config --global core.autocrlf input

BRANCHES
To see a list of local branches, type git branch. Right now, you probably only see one branch, main. 

Let’s create a new branch (myfeaturebranch) for our work:

Type git branch myfeaturebranch
Checkout to that branch: git checkout myfeaturebranch

To open readme: Code Readme.md

BRANCHES ARE BEST SHORT-LIVED (Delete after use)

Be careful with branches

