# [The Data Mining Cup](http://www.data-mining-cup.de/en/)
----------------------------------------------------------

The Data Mining Cup is an international competition hosted by a German analytics company, [prudsys AG](http://www.prudsys.de/en/). In 2015 almost 200 teams from about 150 universities in 48 countries took part in the competition. The best teams were invited to Berlin for the [awards ceremony](http://www.data-mining-cup.de/en/wettbewerb/preistraeger.html) at the [prudsys personalization summit (for retail)](http://www.prudsys.de/en/summit.html).

Iowa State has a rich history of performing very well in DMC. Rick Zhou led ISU to fifth place in the 2013 competition, Cory Lanker led to first place in 2014, and Ian Mouzzon led to 2nd and 3rd place in 2015.

## Important Dates

**April 6** :: Competition officially starts and data is released

**May 18, 6:00 AM (14:00 CEST)** :: End of competition and deadline to submit predictions

**June 28 - 29** :: prudsys personalization summit and award ceremony in Berlin

## Using GitHub

### Getting Started

If you are not familiar with Git and GitHub, please read through the following links:
- [https://guides.github.com/introduction/flow/](https://guides.github.com/introduction/flow/)
- [http://rogerdudler.github.io/git-guide/](http://rogerdudler.github.io/git-guide/)

If you are used to working from the command line then Git should be easy for you. If not, there is a great GUI for GitHub that is supported by both Mac and Windows: [https://desktop.github.com/](https://desktop.github.com/).

There is also a YouTube Channel dedicating to using GitHub: [https://www.youtube.com/playlist?list=PL0lo9MOBetEHhfG9vJzVCTiDYcbhAiEqL](https://www.youtube.com/playlist?list=PL0lo9MOBetEHhfG9vJzVCTiDYcbhAiEqL).

Keep in mind that GitHub is not designed to be a database, and generally the size of a repository is capped at 1 GB. However, we will be using the Git Large File Storage (Git LFS) system which is supported by GitHub in order to store datasets. With Git LFS we get up to 50 GB of storage which should be much more than enough for the competition. Using Git LFS is extremely easy. You can learn about it here: 
- [Getting started with Git LFS](https://git-lfs.github.com/?utm_source=github_site&utm_medium=billing_settings_link&utm_campaign=gitlfs)
- [Short video tutorial on Git LFS](https://www.youtube.com/watch?v=uLR1RNqJ1Mw) (and I really do mean short)
- [Installing Git LFS](https://help.github.com/articles/installing-git-large-file-storage/)

Remember, **please do not ever push large data files unless they are tracked by Git LFS**.

### Workflow

The typical workflow when using Git goes like this: 

:one: **Pull** latest work from the remote repository 

From command line:
```bash
> git pull
```
From GitHub app: just press the 'sync :repeat:' button

:two: Do some coding...

:three: **Commit** changes 

From command line:
```bash
> git add -u     # to commit changes to files that are already being tracked by git, or use
> git add [file] # to only commit changes for a specific file, or use
> git add -A     # to commit changes for all files that you modified
```
From GitHub app: press the 'commit' button

:four: **Push** changes back to the remote repository

From command line:
```bash
> git push
```
From GitHub app: press the 'sync :repeat:' button
