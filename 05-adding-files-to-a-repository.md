# Adding files to a repository

Check the status of your repository: Type the following command to check the status of your Git repository:

```bash
git status
```

This will display a list of all the files in your repository and their status.

1. Stage or add files: To stage or add files to your Git repository, use the "git add" command followed by the name of the file or folder that you want to add. For example, if you want to add a file named "index.html", you would type:

```bash
git add index.html
```

You can also use the "git add" command with a wildcard (*) to add all files in a folder:

```bash
git add .
```

This will add all files in the current directory to the staging area.

1. Check the status of your repository again: After adding files to your repository, use the "git status" command again to check the status of your repository. You should see that the files you added are now listed as "changes to be committed."
2. Commit changes: Once you have staged or added files to your repository, you'll need to commit your changes. Use the "git commit" command followed by a message describing the changes you made. For example:

```bash
git commit -m "Add index.html file"
```

This will create a new commit with the changes you made to the repository.
