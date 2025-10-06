Git Challenge: Remote Work Tree Isolation
This challenge tests a deep understanding of the Git environment and its ability to manage repositories where the internal database and the visible project files are physically separated.

The Challenge
You are required to run a Git command (specifically git status) successfully from a third, irrelevant location.

Challenge Parameters
Component

Path

Purpose

GIT_DIR

/data/repo.git

The hidden repository database.

GIT_WORK_TREE

/www/html/

The visible project files.

Starting Location

/home/scripts

The irrelevant directory where you run the command.

The Task
In a single command, you must explicitly set the two necessary environment variables and run git status.

The solution must be a single line that proves Git can connect the isolated metadata and the work tree files.

The final flag format is the solution command itself.
