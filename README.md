# PLPBasicGitAssignment

## Assignment 1: Basic Git Commands And GitHub Workflow

### Steps

1. Create a new repository on GitHub.
2. Create a new directory on your local machine. `mkdir PLPBasicGitAssignment`
3. Change to the new directory. `cd PLPBasicGitAssignment`
4. Initialize the directory as a Git repository. `git init`
5. Create a new file. `touch README.md`
6. Add some content to the file. `echo "# PLPBasicGitAssignment" >> README.md`
7. Add new file `touch hello.txt`
8. Add some content to the file. `echo "Hello, Git!. I'am a new file" >> hello.txt`
9. Add the file to the staging area. `git add README.md`
10. Add the file to the staging area. `git add hello.txt`
11. Commit the file to the repository. `git commit -m "Add hello.txt with a greeting"`
12. Set the branch to the development branch. `git branch -M development`
13. Add the remote repository. ` git remote add origin git@github.com:Gideon-Yebei/PLPBasicGitAssignment.git`
14. Push the changes to the remote repository. `git push -u origin development`
