## Reverting Code to a Previous Commit

### 1. Clone the repository:
   ```git clone <repository-url>```
   ```cd <repository-folder>```

### 2. Find the commit to which you'd like to revert:
   ```git log```

### 3. Revert the code to a previous commit:
   ```git reset --hard <old-commit-hash>```

### 4. Push the changes forcefully to the remote repository:
   ```git push origin HEAD --force```
