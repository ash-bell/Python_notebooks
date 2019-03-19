#how to make a github repository

1. First make a repository on github with nothing in it
2. Then type `git init` within the folder I want to put on github
3. Using `git add <your files>` add the files to the list to be uploaded
4. Check you're adding the right files with `git status`
5. Type `git commit -m <"my message">` to confirm the upload
6. Make sure github knows who you are using `git config --global user.email "<email>"` and `git config --global user.name "<username>"`
6. Type `git remote add orgin <URL of the github repository>` to create the address the uploaded files will go to
7. Check this is correct with `git remote -v`
8. Type `git push origin master` to upload the files to the URL address
9. Type in your username and password for github

#To update the files to send
1. `git add <your files>` These are any files you have edited or want to send
1b. `git rm <you files>` removes any files you no longer want to upload from the github repository but NOT your local machine
2. `git commit -m "<my message>"` Any message you want to include with the upload. I usually include the date
3. `git commit origin master` This confirms the changes you want to upload
