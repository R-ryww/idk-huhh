# idk-huhh
added test...
-
-
-
User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ pwd
/c/Users/User/Documents/01_Github
$ cd ..

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ pwd
/c/Users/User/Documents/01_Github

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ git clone https://github.com/R-ryww/idk-huhh.git

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ git clone https://github.com/R-ryww/idk-huhh.git
Cloning into 'idk-huhh'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Cloning into 'idk-huhh'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Receiving objects: 100% (3/3), done.

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ cd idk-huhh/
.git/      README.md

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ cd idk-huhh/
.git/      README.md  

User@Room107-53 MINGW64 ~/Documents/01_Github (master)
$ cd idk-huhh/

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ cwd
bash: cwd: command not found

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ pwd
/c/Users/User/Documents/01_Github/idk-huhh

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git commit -m"index.html"
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git add .

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git commit -m"index.html"
[main ebeab79] index.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git push origin main
fatal: unable to access 'https://github.com/R-ryww/idk-huhh.git/': Could not resolve host: github.com

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git config
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 277.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/R-ryww/idk-huhh.git
   214d41d..ebeab79  main -> main

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git add .

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git add .

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git commit -m"Added"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git push origin main
Everything up-to-date

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git add .

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git commit -m "I added something"
[main 43d2264] I added something
 1 file changed, 2 insertions(+), 1 deletion(-)

User@Room107-53 MINGW64 ~/Documents/01_Github/idk-huhh (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 24 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 309 bytes | 309.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/R-ryww/idk-huhh.git
   ebeab79..43d2264  main -> main