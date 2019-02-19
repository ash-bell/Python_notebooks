#how to make a github repository

1. First make a repository on github with nothing in it
2. Then type `git init` within the folder I want to put on github
3. Using `git add <your files>` add the files to the list to be uploaded
4. Check you're adding the right files with `git status`
5. Type `git commit -m <"my message">` to confirm the upload
6. Make sure github knows who you are using `git config --global user.email "<email>"` and `git config --global user.name "<username>"`
6. Type `git remote add orgin <URL of the github repository>` to create the address the uploaded files will go to
7. Check this is correct with `git remote -v`
8. Type `git push -u origin master` to upload the files to the URL address
9. Type in your username and password for github
