# Git Tutorial #


| Command  | Purpose                               | Example                                  |
|----------|---------------------------------------|------------------------------------------|
| clone    | get a repo from origin                | git clone https://github.com/BlitzkriegSoftware/GitTutorial.git |
| pull     | get updates from origin               | git pull                                 |
| add      | add files to track                    | git add .                                |
| -        | add file to track (ignore .gitignore) | git add {filename} -f                    |
| commit   | make a change set                     | git commit -m "Check in Comment"         |
| push     | update origin                         | git push                                 |
| branch   | list branches                         | git branch                               |
| -        | make branch                           | git branch {branch-name}                 |
| -        | delete branch                         | git branch -D {branch-name}              |
| checkout | change branch                         | git checkout {branch-name}               |
| -        | undo a change to a file               | git checkout --  {filename}              |
| status   | what’s going on?                      | git status                               |
| log      | see history                           | git log                                  |
| -        | see history w. deltas                 | git log -p -2                            |
| -        | see w. branch visualization           | git log --pretty=format:"%h %s" --graph  |
| diff     | diff current vs. HEAD                 | git diff                                 |
| reset    | undo all changes                      | git reset --hard HEAD                    |
| blame    | see who changed file                  | git blame {filename}                     |
| tag      | add a tag to commit                   | git tag {tag}                            |
| rm       | remove a commited file                | git rm {filename}                        |

