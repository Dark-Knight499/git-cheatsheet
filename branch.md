Here are some common `git branch` commands to help you manage branches in Git:

1. **List all branches**:
   ```bash
   git branch
   ```
   This shows all local branches in your repository. Add `-a` to see both local and remote branches:
   ```bash
   git branch -a
   ```

2. **Create a new branch**:
   ```bash
   git branch branch_name
   ```
   This creates a new branch with the specified name, but does not switch to it.

3. **Switch to a branch**:
   ```bash
   git checkout branch_name
   ```
   Alternatively, you can use the newer `switch` command:
   ```bash
   git switch branch_name
   ```

4. **Create and switch to a new branch**:
   ```bash
   git checkout -b branch_name
   ```
   Or with `switch`:
   ```bash
   git switch -c branch_name
   ```

5. **Rename a branch**:
   ```bash
   git branch -m old_branch_name new_branch_name
   ```

6. **Delete a branch**:
   ```bash
   git branch -d branch_name
   ```
   Use `-D` to force delete if the branch has unmerged changes:
   ```bash
   git branch -D branch_name
   ```

7. **View the last commit on each branch**:
   ```bash
   git branch -v
   ```

8. **List branches merged into the current branch**:
   ```bash
   git branch --merged
   ```

9. **List branches not merged into the current branch**:
   ```bash
   git branch --no-merged
   ```

10. **Push a new branch to a remote repository**:
    ```bash
    git push origin branch_name
    ```

11. **Delete a remote branch**:
    ```bash
    git push origin --delete branch_name
    ```

Let me know if you need more details about any specific command!