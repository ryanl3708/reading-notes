## Reading Note Class 3

## Git Intro

### Version Control
* is a system that allows access to various versions of a file
* Local Version Control
    * one database to store changes in files
* Centralized Version Control
    * Single server storing changes and file versions
    * efficient management since every change is visible
    * server as a single point of failure
* Distributed Version Control
    * Clients can create mirrored repositories
    * can collaborate in joint projects in simultaneous workflows.

### Git
* Is a DVCS
    * stores data in system made of snapshots.
    * Every save (commit) creates a snapshot as a reference
    * Local operation, so project records can be fetched without needing server access
    * file changes kept track of by Git (low risk of corruption/loss of info)
* States
    * Committed, Modified, Staged
    * (Working Directory) -> add -> (Index) -> Commit -> (Head)
    * (Untracked) add file (unmodified) edit file (modified) stage file (staged)

* Commands :
    * git config
    * git status
    * Cloning
        * git clone 'link'
        * clones the repository from link
    * ACP
        * git add filename
            * use add * if tracking all files
        * git commit -m "change description"
        * git push origin master