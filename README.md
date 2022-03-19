# ART-277
1, Git is a version control that let you manage and keep track of your own coding you did earlier while github serve as location
for uploading copies of your git repository.

2. To download git you will have to go on the official site of git.  go to https://git-scm.com/download/win 
Installation :
1. Download the latest version of git and choose the 64/32 bit version. After the file is downloaded install it in the system, select lunch the git bash, than click on finish.
2. Check the Git version : $ git --version
3. For any help, use the following command: $ git help config
This command will lead you to a browser of config [commands](https://www.simplilearn.com/tutorials/git-tutorial/git-commands). Basically, the help the command provides a manual from the help page for the command just following it (here, it's config).
Another way to use the same command is as follows: $ git config --help
4.  Create a local directory using the following command:
$ mkdir test
$ cd test
5. The next step is to initialize the directory: $ git init
6. Go to the folder where "test" is created and create a text document named "demo." Open "demo" and put any content, like "Hello Simplilearn." Save and close the file.
7. Enter the Git bash interface and type in the following command to check the status:
$ git status
8. Add the "demo" to the current directory using the following command: $ git add demo.txt
9. Next, make a commit using the following command: $ git commit -m "committing a text file"
10. Link the Git to a [Github] Account: $ git config --global user.username
Note: simplilearn-github is the username on the Github account.
11. Open your Github account and create a new repository with the name "test_demo" and click on "Create repository." This is the remote repository. Next, copy the link of "test_demo."
12. Go back to Git bash and link the remote and local repository using the following command: $ git remote add origin <link>
Here, <link> is the link copied in the previous step.
13. Push the local file onto the remote repository using the following command: $ git push origin master
14.  Move back to Github and click on "test_demo" and check if the local file "demo.txt" is pushed to this repository.

3. Create a directory to contain the project.
- Go into the new directory.
- Type git int.
- Write some code.
- Type git add to add the files (see the typical user page).
- Type git commit.

4. To pull from local repository to a remote repository means to download from on the internet to your computer while push is how you transfer command from your computer to a website .
5.  Push have to do with transferring command from computer to a website.
 Pull have to do with downloading from the internet to your computer. 
Stage is to do git add file.
Command is the snapshot of your work created.
Branches  are a part of your everyday development process.
