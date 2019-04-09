

According to thoughtbot.com:

"One of the most powerful features of Git is how it separates the acts of coding and version control. There's no central server to sync with, no locking files so you teammates can't edit them while you do, in fact there is almost nothing required before you start coding.

Instead, you can simply go to work, coding and figuring things out as comes natural. Whenever you're ready you can then focus on version control and commit your changes."


It provides info on --patch:

"Often when we're ready to commit our changes, we'll run git add . or git add --all, but these are a bit coarse. We can use the more focused form where we name files or directories to stage, for instance git add Gemfile, but even this can be too coarse if we have distinct change sets within a single file."

It also provides info on reset:
"Note, with the above cherry-pick operation, as with all Git operations, Git does not destroy or edit commits, but instead simply creates new ones. This means that the two commits as authored are still on our master branch.

We can solve this by reseting our master branch to align it with origin/master, essentially erasing the original commits (although Git still remembers just in case; Git's got our back)."