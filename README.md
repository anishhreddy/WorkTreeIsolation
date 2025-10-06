Git Challenge: Remote Work Tree Isolation
🎯 Objective
Your goal is to successfully run a core Git command (git status) against a project where the database and the files are stored in two entirely separate locations. You must solve the isolation problem using only Git Environment Variables and without changing your directory.

The Environment
This challenge simulates a system where the internal components of a Git repository are physically split:

Component

Location Hint (Abstract Path)

Technical Role (Variable Hint)

Isolated Metadata

/data/repo.git

The hidden Repository Core (Git's database).

Active Project Files

/www/html/

The Work Tree (the files you see and edit).

Your Location

/home/scripts

You must run the solution command from here.

The Task
Find the single shell command that links the isolated metadata to the project files and successfully runs git status.

Solution Format:

Your answer is the required command itself, following the strict format:
[VARIABLE_1]=[PATH_1] [VARIABLE_2]=[PATH_2] git status

Hint: You must identify which two environment variables are responsible for setting the Repository Core and the Work Tree paths.
