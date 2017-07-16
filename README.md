# idea-gitignore
The correct way to manage `.idea` folder in git


Unlike Netbeans, in Jetbrains IDEs, the setting files related to user and team are stored in the same folder. This makes trouble when we need to track changes in the git. 

IDEA suggests a (blacklist)[https://intellij-support.jetbrains.com/hc/articles/206544839] strategy. However after using 
its products for years, it revealed that it is safer and actually more convenient to do the reverse, white list strategy. I mean ignoring all `.idea` files and adding only team related settings explicitly.  (instead of adding all and ignoring some). 

This repository provides a `.gitignore` file that is needed to be placed in `.idea/` folder of your project.