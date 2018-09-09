# idea-gitignore
The correct way to manage `.idea` folder in git


Unlike Netbeans, in Jetbrains IDEs, the setting files related to user and team are stored in the same folder. This makes trouble when we need to track changes in the git. 

IDEA suggests a [blacklist](https://intellij-support.jetbrains.com/hc/articles/206544839) strategy. 
However this strategy has exposed a number of problems for my team. We came up to use a whitelist strategy, only tracking the files that should be logically and practically identical for all team members. 
This repository provides a `.gitignore` file that should be placed in `.idea` folder of your project.
