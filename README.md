githook-version-example
=======================
Illustrates usage of a git hook, specifically a "post-merge" hook to embed the current git describe results into an assembly as an embedded resource and dispay the results.

##To use:
1. Clone the repo
2. Copy the "post-merge" file into your .git/hooks directory
3. Make a change to this repo remotely (a newline to this file will work)
4. Pull the changes
5. Build and run the solution
