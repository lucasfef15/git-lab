Answer 1: git version 2.30.0.windows.2
Answer 2:
    diff.astextplain.textconv=astextplain
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    pull.rebase=false
    credential.helper=manager-core
    credential.https://dev.azure.com.usehttppath=true
    init.defaultbranch=master
    user.name=Lucas Fernandes
    user.email=lf508319@ohio.edu
Answer 3:
    These are common Git commands used in various situations:

    start a working area (see also: git help tutorial)
    clone             Clone a repository into a new directory
    init              Create an empty Git repository or reinitialize an existing one

    work on the current change (see also: git help everyday)
    add               Add file contents to the index
    mv                Move or rename a file, a directory, or a symlink
    restore           Restore working tree files
    rm                Remove files from the working tree and from the index
    sparse-checkout   Initialize and modify the sparse-checkout

    examine the history and state (see also: git help revisions)
    bisect            Use binary search to find the commit that introduced a bug
    diff              Show changes between commits, commit and working tree, etc
    grep              Print lines matching a pattern
    log               Show commit logs
    show              Show various types of objects
    status            Show the working tree status

    grow, mark and tweak your common history
    branch            List, create, or delete branches
    commit            Record changes to the repository
    merge             Join two or more development histories together
    rebase            Reapply commits on top of another base tip
    reset             Reset current HEAD to the specified state
    switch            Switch branches
    tag               Create, list, delete or verify a tag object signed with GPG

    collaborate (see also: git help workflows)
    fetch             Download objects and refs from another repository
    pull              Fetch from and integrate with another repository or a local branch
    push              Update remote refs along with associated objects

    'git help -a' and 'git help -g' list available subcommands and some
    concept guides. See 'git help <command>' or 'git help <concept>'
    to read about a specific subcommand or concept.
    See 'git help git' for an overview of the system.
Answer 4:
    On branch master

    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
            README.md 
            answers.md

    nothing added to commit but untracked files present (use "git add" to track)
Answer 5:
    On branch master

    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   README.md

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
            answers.md
Answer 6:
    On branch master

    No commits yet

    Changes to be committed:
    (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   answers.md
Answer 7:
    On branch master
    nothing to commit, working tree clean
Answer 8:
    commit 6450658f0431062b99697a9459add844ddb486c2 (HEAD -> master)
    Author: Lucas Fernandes <lf508319@ohio.edu>
    Date:   Tue Jan 26 18:44:41 2021 -0500

        Initial commit
Answer 9: 

    On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git restore <file>..." to discard changes in working directory)
            modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")
Answer 10:
    Lucas Fernandes Esteves Fonseca
    git-hub username: lucasfef15
Answer 11:
    ! [rejected]        main -> main (fetch first)
    error: failed to push some refs to 'https://github.com/lucasfef15/git-lab'
    hint: Updates were rejected because the remote contains work that you do    
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes   
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.  
Answer 12:
    Lucas Fernandes Esteves Fonseca
    git-hub username: lucasfef15
    cs2400 sections 109 and 107
Answer 13:
        Directory: C:\Users\Lucas Fernandes\Documents\cs2400\git-lab-2


    Mode                 LastWriteTime         Length Name
    ----                 -------------         ------ ----
    -a----         1/26/2021   7:18 PM            302 .gitignore
    -a----         1/26/2021   7:18 PM             11 README.md