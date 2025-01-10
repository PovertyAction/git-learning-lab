# Testing Merge Conflicts

This is a sample file created to practice resolving merge conflicts.

## Instructions (if working with a partner)
1. Clone this repository
2. Create a new branch <USERNAME>-conflict
3. On your branch, edit the "sample content lines below. The filename must be the same filename that your partner uses. Make sure the content inside the file is different, and that neither file is empty.
4. Create a pull request in the class repository with base: main and compare: USERNAME-conflict
5. You will see that the first pull request can merge well.
6. When you see the merge conflict in the second pull request, work together to resolve the merge conflict.
   1. Working locally, merge main into your branch.
   2. When you see there's a conflict, that's OK! The files that have conflicts are listed under Unmerged Paths. Type git status to verify which file has the conflict.
   3. Open the file in your text editor, and look for the merge conflict markers. (<<<<<<<, =======, >>>>>>>)
   4. Both branches' versions of code are present - pick which one you want to keep, and save the changes.
   5. Add and commit the saved changes to resolve the merge conflict.
   6. Push your branch up to the remote, and see the resolution in the pull request.
   7. Merge the pull request.

## Instructions (if working alone)

1. In this repository, confirm the branch you are in is main.

2. Create a branch and name it as <USERNAME>-modify-first.

3. In the <USERNAME>-modify-first branch, edit the "Sample Content" below and commit it.

4. Change the branch to main again, create a second branch and name it as <USERNAME>-modify-conflict.

5. In the <USERNAME>-modify-conflict branch, edit the "Sample Content" below with _different text_ and commit it.

6. Make sure the content inside of the file is different, and that neither file is empty.

7. Create a pull request in the class repository with base: main and compare: <USERNAME>-modify-first. (title: USERNAME merge first)

8. Create a pull request in the class repository with base: main and compare: <USERNAME>-modify-conflict. (title: USERNAME resolve conflict)

9. You will see that the first pull request titled USERNAME merge first can merge well.

10. Go through steps mentioned above to resolve the merge conflict.

## Sample Content
Hello, today is 1/9/2025.
This is line 2, by David Torres Leon.
I live in Bogota, Colombia.