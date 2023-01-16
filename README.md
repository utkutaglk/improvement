# Github Bootcamp

I write something in here to make progress on Github.

-> Understanding zsh. vs bash. difference
-> Knowing basic shell commands like (cd,mkdir,ls,ls -l,echo,ls -la,(.),(..),nano,clear,man,touch,(>),(>>),pwd,rm.rm -fr,rm -(f)
-> Initialise .git and learning git objects like(Blob,Tree,Commit,Annotated Tag)
-> Coding git low-lewel commands to create and print object and it's feature(git hash-object, git cat-file, git mktree)
-> What is hash code and how to create hash code by Git ? (SHA1, 40 Hexadecimal = 160 bits)
-> Git cat-file options ( git cat-file -p, git cat-file -s, git cat-file -t)
-> Creating blob objects in two way ( echo "text" | git hash-object --stdin -w , git hash-object ../file.txt -w) 
-> Git object permission ( 040000 Directory, 100644 Regular non-executable file, 100755 Regular executable file, 120000 Symbolic link, 160000 Gitlink)
-> Some good commands to use ( find .git/objects -type f, git ls-files -s)
-> ( cat ../*.txt | git mktree ) it is used to create tree object in Git Repository.
-> There are three main areas to comprehend (Working Directory, Staging Area, Git Repository) if your files located in Git Repository, you can transfer them .git read-tree <hash code> to Staging Area.After that, you can transfer them to Working Directory from Stagin area by using .git checkout-index -a
-> Some remarkable commands (git status, git commit -m, git config --list, git add, git checkout, git log, git rm --cached file.txt)
-> Too important file situations ( in Working Directory -> Untracked-Modified-Deleted-Unmodified, in Staging Area -> Staged-Unmodified, in Git->Unmodified)
-> Understanding branch and head perfectly ( Branch located in -> .git/refs/heads, HEAD located in -> .git/HEAD -> ref: refs/heads/master )
-> Special branch commands ( git branch <name>, checkout <name>, branch -d <name>, git checkout -b <branch-name>, git branch -m <oldname> <newname> )
-> (git clone, git diff, git commit -a -m "comment" , git merge <branch-name>
-> some changes on local repo.
