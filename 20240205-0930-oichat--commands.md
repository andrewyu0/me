aynote: testing out openinterpreter flow of 1) terminal task complete 2) output convert learnings to md 3) auto save obs add to graph
- if done right potential gamechanger
- risk: costly, so explore the local models 
- testing out here with git comds
session screenshot 09:45
![[20240205-terminal.png]]


| No. | Command | Description | Usage |
| --- | ------- | ----------- | ----- |
| 1   | `git branch` | Lists all local branches in the current repository. | Used to check the current active branch and see all available branches. |
| 2   | `git checkout main` | Switches to the 'main' branch. | Used to switch to the 'main' branch before merging 'master' into it. |
| 3   | `git merge master` | Merges 'master' branch into the current branch (main). | Used to attempt to merge 'master' into 'main'. Initially failed due to unrelated histories. |
| 4   | `git merge master --allow-unrelated-histories` | Merges 'master' branch into the current branch (main), allowing for unrelated histories. | Used to actually merge 'master' into 'main', overcoming the unrelated histories error. |
| 5   | `git branch` (repeated) | Lists all local branches in the current repository. | Used to check branch status after merging. |
| 6   | `git branch -d master` | Deletes the 'master' branch. | Used to delete 'master' branch after its contents were merged into 'main'. |
