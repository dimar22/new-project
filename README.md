
You must be registered at https://github.com.
Create a new repository in your Github account with the name new-project
Create a new directory in your environment called "new-project".
Change to the "new-project" directory.
Initialize a new public Git repository inside the "new-project" directory command:
 git init
Rename the main branch with the name "main" using the command:
 git barnch -M main
Create new branch and switch in. Use this command for it:
 git checkout -b development
After working on the project, prepare them for the committee and comment on them:
 git add .
 git commit -m "development change file readme"
Change branch to "main":
 git checkout main
Merge the changes from the "development" branch into the "main" branch:
 git merge development
 git add .
 git commit -m "done"
to upload to the repository you need to execute the following commandsЖ
git remote add origin https://github.com/dimar22/new-project.git       (http of the previously created repository )
git config --global user.name "name"         (your name at the GitHub)
git config --global user.mail "e-mail"       (your e-mail at the GitHub)
git push -u origin main