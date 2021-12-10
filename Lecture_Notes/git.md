## To Configure Git in a new VM
This will allow for automated Git push/pull without being prompted for user name and passowrd
- Step 1: vi .gitconfig file to add the following lines:
```
[credential]                                                                                                                                    
     helper = store
 
[user]
    name = wcj365
    email = wcj365@gmail.com
```
- Step 2: Create a new file .git-credentials and add this line (replace the string with GitHub token):
```
https://wcj365:[GitHub Personal Access Token]@github.com
```
