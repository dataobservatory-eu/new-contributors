## Find the repository

1.  Go to the repository url on github. If the repository is public, you
    will see the page immediately. If it is private, you will see it as
    if it did not exist if you have no right to see it.

[github.com/dataobservatory-eu/new-contributors](https://github.com/dataobservatory-eu/new-contributors)

## Bookmark the repository

1.  Star this repo: dataobservatory-eu/new-contributors

<!-- -->

    knitr::include_graphics(here("png", "linux",  "github_star_repository.png"))

![](png/linux/github_star_repository.png)

## Fork the repository

You create a branch, a version of the repository (folder), in your own
github.com space in the cloud by creating a fork. This is the first step
of the collaboration: you will always work with a copy of our files, and
you will only overwrite master files with the repository manager’s
explicit approval.

You will see, among other things, the following information:

*A* fork *is a copy of a repository. Forking a repository allows you to
freely experiment with changes without affecting the original project.*

    knitr::include_graphics(here("png", "linux",  "github_create_fork.png"))

![](png/linux/github_create_fork.png) You will have a copy of the entire
directory at `github.com/<your_username>/new-contributors`

## Download your copy

In the following screenshot, RStudio is used on an Ubuntu (Linux)
computer.

    knitr::include_graphics(here("png", "linux",  "github_download_fork.png"))

![](png/linux/github_download_fork.png)

-   Downloading on a Windows version will be slightly different. Instead
    of using the SSH link, you will use the standard HTTPS link of the
    repository.
-   On Windows or Mac, you can use Github Desktop for synchronizing your
    folders. That is preferred to RStudio if you have large graphic
    files, PowerPoint presentations, or other large assets in the
    folder.

1.  `github.com/dataobservatory-eu/new-contributors` is in sync with
    your online copy, i.e. 
    `github.com/<your_username>/new-contributors`
2.  Your computer has a copy in sync with
    `github.com/<your_username>/new-contributors`.

## Upstream sync

What happens if you have not opened the
`<your_drive>/.../new-contributors` for some time? Maybe somebody
changed the contents of
`github.com/dataobservatory-eu/new-contributors`. If you want to stay in
sync, you have to make sure first that your online copy is updated from
the master repository.

    knitr::include_graphics(here("png", "linux",  "githu_sync_fork.png"))

![](png/linux/githu_sync_fork.png)

1.  By pressing the Synch fork button, you can make sure that
    `github.com/dataobservatory-eu/new-contributors` is in sync with
    your online copy, i.e. 
    `github.com/<your_username>/new-contributors` again.
2.  You must pull any changes in the ‘upstream fork’ or the master
    folder down to your computer to make sure that
    `github.com/<your_username>/new-contributors` is again in sync with
    your local copy on `<your_drive>/.../new-contributors`

## Pull down new contents

You must write a meaningful message for your colleagues.

I am uploading now the screenshots of this tutorial

## Synchronize changes

In this case, I use RStudio on an Ubuntu computer to send the files. The
steps are the same on Windows or Mac, and they are essentially the same
if you use GitHub Desktop for synchronizing a folder. The user interface
will look different.

1.  You select the files that you want to upload, or push up.

<!-- -->

    knitr::include_graphics(here("png", "linux",  "rstudio_files_commit.png"))

![](png/linux/rstudio_files_commit.png)

1.  You commit to sending the files up into the cloud. If the repository
    on github.com is public, you will make the files public, so think
    this step through.

<!-- -->

    knitr::include_graphics(here("png", "linux",  "rstudio_files_commit_2.png"))

![](png/linux/rstudio_files_commit_2.png)

1.  You must write a meaningful commit message. Why? If you had a
    previous task description (‘issue’), link or reference to it. Later
    you can undo these changes, and the better you describe them, the
    easier you will find this step and correct it, should you need it.
    Even more important: whoever will synchronize your changes to the
    team’s master repo will know what happened.

<!-- -->

    knitr::include_graphics(here("png", "linux",  "rstudio_stage_files.png"))

![](png/linux/rstudio_stage_files.png)

1.  Push the green arrow up, and the files will be uploaded to
    `github.com/<your_username>/new-contributors`.

## Did the new files arrive?

Go to `github.com/<your_username>/new-contributors` and check if the new
files are there. In this case, I changed the `Rmd` and `md` version of
this tutorial, and added the screenshots as `png` files to the `/png`
folder in the repository.

    knitr::include_graphics(here("png", "linux",  "github_new_commit_arrives.png"))

![](png/linux/github_new_commit_arrives.png) As you can see, in the
cloud, on `github.com/antaldaniel/new-contributors` I can see that the
new files are there with my short commit message.

I also see a message that
`This branch is 1 commit ahead of dataobservatory-eu:main`. One bunch of
changes were committed to change the dataobservatory-eu team’s master
repository. How will I make sure that the original, public, joint
folder,
i.e. [github.com/dataobservatory-eu/new-contributors](https://github.com/dataobservatory-eu/new-contributors)
will be updated?

## Sync with your team

1.  On `github.com/<your-username>/new-contributors` you go to ‘pull
    requests’

<!-- -->

    knitr::include_graphics(here("png", "linux",  "github_pull_request_1.png"))

![](png/linux/github_pull_request_1.png)

1.  On `github.com/<your-username>/new-contributors` you go to ‘pull
    requests’

<!-- -->

    knitr::include_graphics(here("png", "linux",   "github_pull_request_2.png"))

![](png/linux/github_pull_request_2.png) 3. You must give clearer
instructions on this pull request. One pull request may contain many
files, i.e. not only one commit, but many files from several commits in
one go. Therefore, it is a good practice to write a short summary of all
the changes you would like to do in the team’s master repository.

    knitr::include_graphics(here("png", "linux",  "github_merge_fork_3.png"))

![](png/linux/github_merge_fork_3.png)

1.  Press `Create pull request` and **stop**. After the pull request is
    made, you will get a confirmation of what changed, but if you are
    offered, to not make the last step.

<!-- -->

    knitr::include_graphics(here("png", "linux",  "github_merge_fork_4.png"))

![](png/linux/github_merge_fork_4.png) 5. **Do not press
`Merge pull request`** if you see it. Normally only your supervisor
should see it.
