The first step I did was to make sure that I create a repository in 'main branch', intializing it with a README file.
I created a folder on my PC, PLPBasic Assignment.
I opened VS Code, opened my locally saved folder from there. 
I put in git init to initialize a new git repository in my local folder.
Put in git remote origin and pasted the url copied from Git Hub.
I created a new text file named `hello.txt`.
I added a simple text message "Hello, Git!".
I commited the changes using- git commit -m "Add hello.txt with a greeting"
I pushed to GitHub git push -u origin main
Then this error appeared:
"error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Shalommy/PLPBasicGitAssignment.git'"
I then pushed to GitHub git push -u origin master ...and this proved to be succesful.
