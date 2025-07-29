### 📝 Git commands

---

| **Command**                         | **What it does**                                                                 | **Translation**                                         |
|------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------|
| `git commit -m "message"`          | Saves a snapshot of your changes with a message                                 | "Here’s my diary entry for today. Please remember it."  |
| `git branch name`                  | Creates a new branch named `name`                                               | "Show me my alternate universes."                       |
| `git checkout name`                | Switches to branch `name`                                                       | "Take me to that universe."                             |
| `git checkout -b name`            | Creates and switches to branch `name`                                           | "Let’s go create a new alternate universe!"             |
| `git merge name`                   | Merges changes from `name` branch into current branch                           | "Let’s combine timelines and hope nothing explodes."    |
| `git rebase main`                  | Reapplies your commits on top of `main` to clean up history                     | "Rewrite the timeline so it looks like I started later."|
| `git log`                          | Shows commit history                                                            | "Show me everything I’ve ever done (and cried about)."  |
| `git status`                       | Shows what's changed and what’s staged                                          | "Hey Git, what’s going on here?"                        |
| `git diff`                         | Shows the actual code changes                                                   | "Okay... what did I mess up again?"                     |
| `git add filename.py`             | Stages a file for commit                                                        | "Take just this one file. I trust it."                  |
| `git add .`                        | Stages all changed files                                                        | "Take everything I’ve changed. Yes, all of it."         |
| `git reset --soft HEAD~1`         | Undo the last commit but keep changes staged                                    | "Oops. Let’s pretend that commit never happened."       |
| `git reset --hard`                | Reset everything — discard all uncommitted changes                              | "Wipe it. Burn it. Pretend it never existed."           |
| `git clean -fd`                   | Remove all untracked files and directories                                      | "Remove all the junk I forgot I created."               |
| `git stash`                        | Temporarily hide all your current changes                                       | "Hide my mess. I’ll come back later."                   |
| `git stash pop`                    | Reapply the stashed changes                                                     | "Okay I’m back. Give me my mess."                       |
| `git remote add origin <url>`     | Links your local repo to a GitHub repo                                          | "Let me hook this thing up to the cloud."               |
| `git clone <url>`                 | Makes a copy of a remote GitHub repo                                            | "Give me a copy of that awesome thing someone else built." |
| `git pull`                         | Fetches and applies changes from the remote repo                               | "Give me everyone’s latest changes before I look dumb." |
| `git push`                         | Sends your commits to the remote GitHub repo                                    | "Take my work. Send it to the gods (GitHub)."           |
| `git merge --abort`               | Cancel a merge that's gone horribly wrong                                       | "Undo the merge. It was a terrible idea."               |
| `git rebase --abort`              | Abort a rebase mid-crisis                                                       | "Stop the time-travel. I wasn’t ready."                 |
| `git rebase --continue`           | Continue rebase after fixing a conflict                                         | "I’ve fixed the timeline. Let’s keep rewriting history."|


## Remember:

```bash
branch early, and branch often
```
