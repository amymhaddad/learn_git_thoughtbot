aoril 2020

Notes from Thoughtbot(https://thoughtbot.com/upcase/videos/git-getting-to-confident):
"One of the key features of my command line Git workflow is having the current Git context always displayed as part of the prompt. In particular, the prompt will display each of the following (depending on the current Git context):

Current branch name
Current commit hash
Indication of repo status (clean vs uncommitted changes)"

"This context is critical to my being able to confidently work with my repo, helping me to avoid common mistakes like committing to the wrong branch, forgetting to commit a specific file, etc.

The thoughtbot dotfiles contain a streamlined Git info segment, and my personal dotfiles contain a Git prompt configuration that includes the branch, current commit hash, and dirty status (note, this relies on some features of oh-my-zsh to display properly). Another option would be to use the excellent pure prompt for zsh which contains all this and more, but is still nice and snappy."
