# Summary 
#### In this report we will see the list of the most basic commands to create basic files, branches, how to navigate between them, which commands correspond to which action, and their group divisions.
# Terminal commands
### -PWD
#####  This command helps us to verify where we are currently located.
##### Example: -$ pwd /c/Users/aldra/Deskt
### -Hostname
##### This command allows us to identify the name of our device.
##### Example: -$ hostname MSI
### -mkdir
##### This command allows us to create tents, but if we add "+ name" it will automatically introduce a name to the created layer.
##### Example: mkdir Angel Lugo Saenz
### -Ls
##### This command allows us to display the lists of folders we have and the files contained in the folders.
##### Example:   ls'LeagueClient - Shortcut.lnk'*  'Microsoft Teams.lnk'*   test/'MSI companion.lnk'*             desktop.ini
### -CD:
##### This command allows us to access a folder, but to be specific, we need to use "cd: + name (of the folder we want to search)".
##### Example: cd: Angel Lugo Saenz 
### -CD...
##### This command allows us to go back to a previous folder.
##### Example: cd...
### -CLEAR
##### This command allows us to clear the screen and leave it clean.
##### Example: clear 
### insertar imagenes aqui de antes y despues.
### -History 
##### This command allows us to see the history of all the commands we have been using previously.
##### Example: $ history
    1  git config --global user.name 1909107
    2  git config --global user.email 1909107@upy.edu.mx
    3  git config --list
    4  git init
    5  git add --all
    6  git remote add origin https://github.com/1909107/task.git
    7  git push -u origin master
    8  git commit -m "fist commit"
    9  git push -u origin master
   10  git checkout testing
   11  git init
   12  cd ..
   13  mkdir test
   14  cd test
   15  git init add .
   16  git init
   17  git add .
   18  git commit -m "my first commit"
   19  git branch -M main
   20  git remote add origin https://github.com/1909107/Task2.0.git
   21  git push -u origin main
   22  git init
   23  git statis
   24  git status
   25  ls ..
   26  ls .*
   27  cd ..
   28  ls
   29  git status
   30  git add myfile.txt
   31  cat
   32  pwd
   33  hostname
   34  ls
   35  cd:
   36  cd...
   37  clear
   38  history
   ### -RMDIR 
   ##### This command allows us to delete an empty directory.
   ##### Example: rmdir Angel Lugo Saenz 
   ### -RM
   ##### This command allows us to delete a file.
   ##### Example: rm Task_2.
   ### -RM -RF
   ##### This command allows us to delete directories with files inside them, but to be more specific about which directory we want to delete we need to put the name of the directory.
   ##### Example: rm -rf Angel Lugo Saenz 
   ### -FIND .-NAME(OF THE FILE)
   ##### This command allows us to find all the files in this format((“*.format of the file: txt, md, rtf, etc,.)”).
   ##### Example: find . -name “\*.txt”
   ### -TOUCH
   ##### This command allows us to create blank files and if we want to name them, we will have to do it with the command "mkdir + name".
   ##### Example: touch Angel Lugo.txt
   ### -CAT
   #####  This command allows us to show inside a file.
   ##### Example: 
   ##### -cat filename.(format of the file: txt, md, rtf, etc,.)
##### -cat filename.txt
### -MV
##### This command allows us to change the name of our files.
##### Example: mv +  Angel Lugo Saenz + Lugo saenz(new name)(both files must be placed with extensions).
### -LESS
##### This command allows us to read files and its most common and recommended use is when they are very long files.
##### Example: less ADA4_physics.
### -WC
##### This command allows us to have the information of a file.
##### Example: wc  ADA4_physics.
### -NANO
##### This command allows us  to create and enter to edit text files.
##### Example: 
##### -nano filename.(format of the text file or also programming languages)
##### -nano filename.txt
##### -Once that you enter to nano editor:
##### EXIT: ctrl + x
##### MODIFY OR NOT?: Y/N
##### PRESS ENTER
# Basic git bash command lines.
##### The following commands will allow us to use the "GIT BASH" platform on our computer or laptop.
### -SETUP
##### This command allows us to configuring user information used across all local repositories.
### - Git config -global username (firstname lastname).
##### This command allows us to set a name that is identifiable for credit when review version history.
##### Example:  1  git config -global username 1909107
### -Git config -global user.email (valid-email).
##### This command allows us to set an email address that will be associated with each history marker.
##### Example: git config -global user.email 1909107@upy.edu.mx
### -SETUP&INIT
##### This command allows us to configuring user information, initializing and cloning repositories.
### -Git init
##### This command allows us to initialize an existing directory as a Git repository.
##### Example: $ git initInitialized empty Git repository in C:/Users/aldra/Desktop/.git/
### -Git clone (url)
##### This command allows us to retrieve an entire repository from a hosted location via URL.
##### Example:  git clone 

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting
    -n, --no-checkout     don't create a checkout
    --bare                create a bare repository
    --mirror              create a mirror repository (implies bare)
    -l, --local           to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    -s, --shared          setup as shared repository
    --recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --recursive ...       alias of --recurse-submodules
    -j, --jobs <n>        number of submodules cloned in parallel
    --template <template-directory>
                          directory from which templates will be used
    --reference <repo>    reference repository
    --reference-if-able <repo>
                          reference repository
    --dissociate          use --reference only while cloning
    -o, --origin <name>   use <name> instead of 'origin' to track upstream
    -b, --branch <branch>
                          checkout <branch> instead of the remote's HEAD
    -u, --upload-pack <path>
                          path to git-upload-pack on the remote
    --depth <depth>       create a shallow clone of that depth
    --shallow-since <time>
                          create a shallow clone since a specific time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --single-branch       clone only one branch, HEAD or --branch
    --no-tags             don't clone any tags, and make later fetches not to follow them
    --shallow-submodules  any cloned submodules will be shallow
    --separate-git-dir <gitdir>
                          separate git dir from working tree
    -c, --config <key=value>
                          set config inside the new repository
    --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --filter <args>       object filtering
    --remote-submodules   any cloned submodules will use their remote-tracking branch
    --sparse              initialize sparse-checkout file to include only files at root.
### -Stage and commit
This command allows us to shows the status of the modified files in the directory.
### -Git status
##### This command allows us to shows the status of the modified files in the directory.
##### Example:  git status 
        LeagueClient - Shortcut.lnk
        MSI companion.lnk
        Microsoft Teams.lnk
        desktop.ini
        test/
### -Git add FILENAME.(format of the file)
##### This command allows us to adds a file to git so in the next commit it will be reflected.
##### Example: git add  ADA4_physics.txt
### -Git reset FILENAME.(format of the file)
##### This command allows us to delete or undo the file while keeping the changes in the working directory.
##### Example: git reset ADA4_physics.txt
### -Git commit -m “NAME OF THE CHANGE”
##### This command allows us the takes the staged snapshot and commits it to the project history.
##### Example: git commit -m ADA4_physics.txt
### -STAGE&SNAPSHOT
##### This command allows us to working with snapshots and the Git staging area.
### -Git branch
##### This command allows us to list your branches. (a  will appear next to the currently active branch).
##### Example: git branch.
### -Git branch (branch-name).
##### This command allows us to create a new branch at the current commit.
##### Example: git branch Angel Saenz.
### -Git checkout
##### This command allows us to switch to another branch and check it out into your working directory.
##### Example: git check out 
