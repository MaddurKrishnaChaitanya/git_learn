# Cheatsheet

* **git init**

> Initializing a Repository in an Existing Directory.

* **git clone <<git_repo_url>>**

> If you want to get a **copy of an existing Git repository** — for example, a project you’d like to
contribute to — the command you need is git clone.
    >
        Ex:-
              $> git clone https://github.com/libgit2/**libgit2**
                 That creates a directory named **libgit2**, initializes a **.git** directory inside it, pulls down all the data for that repository, and checks out a working copy of the latest version.
              $> git clone https://github.com/libgit2/libgit2 **mylibgit**
                 That command does the same thing as the previous one, but the target directory is called **mylibgit**.
