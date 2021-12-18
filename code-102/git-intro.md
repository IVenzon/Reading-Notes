# Intro to Git:

Git is a DVCS that stores data through a system of 'snapshots'. Each time you make changes to your project and save them, Git creates a snapshot of this file and stores a reference to it.

Git relies mostly on local operations, as a project's history resides on the local disk. Every single change you make to a file/directory is tracked by Git, so it is easy to see the differences between versions or revert to previous versions if needed.

Using Git in conjunction with sites such as GitHub allow for easy editing/storing of files. This is very useful in team settings, where multiple people are working on the same set of code, as Git/GitHub let each person work on their own copy of the code without changing the original code.

Here is a general method to using Git/GitHub to make changes to your code:

1. First, you need to clone a repository. Go to the repository on GitHub and click the green 'Code' button. Copy the link and use the 'clone' command in your terminal as such:
> git clone [Insert Link Here]

Now you have a local copy of the repository on your computer, and can make as many changes as you wish.

2. In order to make those changes, you first need to prepare your files. Use the 'add' command in your terminal as such:
> git add [Insert Filename Here]

3. After making your changes, use the 'commit' command in your terminal as such:
> git commit -m "Insert Comment Here"

Always include a short yet detailed comment that describes the changes you made. Also, as a rule of thumb, it is better to make lots of smaller changes with lots of commits instead of doing one big change/commit, as it gives you a more thourough look at the changes you have made.

4. When you area ready to finalize your changes, use the 'push' command in your terminal as such:
> git push origin master

This will push your changes to GitHub, and if all goes well, you will now see your changes/comments in your repository.

It is good to remember this simple acronym when it gomes to Git: **ACP**

- **A:** Add
- **C:** Commit
- **P:** Push