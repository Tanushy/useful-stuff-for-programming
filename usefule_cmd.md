markdown
Code kopieren
# Command Line Cheat Sheet

## npm and npx Commands

    - **Create a React App**:
    ```sh
    npx create-react-app my-app

    ## Start the development server:
        npm start

    ## Run tests:
        npm test

    ## Build the app for production:
        `npm run build`


#      **Basic Terminal Commands**

    ## Change directory
        `cd path/to/directory`

    ## Make a new directory:
        mkdir new-directory

    ## List directory contents:
        ls -al

    ## Copy a file:
        cp source.txt destination.txt

    ## Move or rename a file:
        mv oldname.txt newname.txt

    ## Remove a file:
        rm filename.txt

    ## Remove a directory:
        rm -r directory-name

    ## Display the current directory:
        pwd

    ## Create an empty file:
        touch filename.txt


#       **Git Commands**    

    ## Clone a repository:
        git clone https://github.com/user/repo.git

    ## Initialize a new Git repository:
        git init

    ## Check the status of your repository:
        git status

    ## Add files to staging area:
        git add filename

    ## Commit changes:
        git commit -m "commit message"
    
    ## List branches
        git branch

    ## Push changes to a remote repository:
        git push origin branch-name

    ## Pull changes from a remote repository:
        git pull origin branch-name

    ## Create a new branch:
        git branch new-branch

    ## Switch to a branch:
        git checkout branch-name

    ## Merge a branch into the current branch:
        git merge branch-name

    ## Delete a Branch
        git branch -d [branch-name]

    ## View commit history:
        git log

    ## Show changes:
        git diff

    ## Stash changes:
        git stash

    ## Apply stashed changes:
        git stash apply

#       Other Useful Commands

    ## Open Visual Studio Code:
        code .

    ## Clear the terminal screen:
        clear

    ## Check node version:
        node -v

    ## Check npm version:
        npm -v

    ## List globally installed npm packages:
        npm list -g --depth=0

    ## Search for a package in npm:
        npm search package-name

    ## Install a package globally:
        npm install -g package-name

    ## Uninstall a global package:
        npm uninstall -g package-name

    ## List all running processes (Unix-based):
        ps aux

    ## Kill a process by ID (Unix-based):
        kill -9 PID

    ## Display system information (Unix-based):
        uname -a

    ## Check disk usage:
        df -h

    ## Check memory usage:
        free -h

    ## List all environment variables:
        printenv

    ## Display contents of a file:
        cat filename.txt

    ## Edit a file with nano editor:
        nano filename.txt

    ## Download a file with wget:
        wget http://example.com/file.zip




