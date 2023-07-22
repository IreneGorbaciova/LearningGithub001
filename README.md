# LearningGithub001

This is a description for ReadMe file

DenissMacStudio:Learning Github Irina$ pwd
/Users/Irina/Desktop/Learning Github
DenissMacStudio:Learning Github Irina$ cd LearningGithub001/
DenissMacStudio:LearningGithub001 Irina$ 
DenissMacStudio:LearningGithub001 Irina$ git branch --all
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
DenissMacStudio:LearningGithub001 Irina$ git branch mybranch
DenissMacStudio:LearningGithub001 Irina$ git branch --all
* main
  mybranch
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
DenissMacStudio:LearningGithub001 Irina$ git checkout mybranch
Switched to branch 'mybranch'
DenissMacStudio:LearningGithub001 Irina$ pwd
/Users/Irina/Desktop/Learning Github/LearningGithub001
DenissMacStudio:LearningGithub001 Irina$ ls
README.md
DenissMacStudio:LearningGithub001 Irina$ git add README.md
DenissMacStudio:LearningGithub001 Irina$ git commit -m 'update readme file'
[mybranch e6b4556] update readme file
 1 file changed, 2 insertions(+)
DenissMacStudio:LearningGithub001 Irina$ git push --set-upstream origin mybranch
Counting objects: 3, done.
Delta compression using up to 10 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'mybranch' on GitHub by visiting:
remote:      https://github.com/IrinaGorbaciova/LearningGithub001/pull/new/mybranch
remote: 
To https://github.com/IrinaGorbaciova/LearningGithub001.git
 * [new branch]      mybranch -> mybranch
Branch 'mybranch' set up to track remote branch 'mybranch' from 'origin'.
DenissMacStudio:LearningGithub001 Irina$ 