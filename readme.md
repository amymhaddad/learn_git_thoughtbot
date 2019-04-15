

According to thoughtbot.com:

"Before moving on, we do want to highlight that this course is not intended to be your introduction to Git, but instead expects that you're familiar with core operations like staging and committing files, branching, viewing the log, and pushing to GitHub. If you're not quite there, we recommend starting with a few introductory resources, then coming back here when you're ready:

Try Git is a great interactive tutorial that requires no prior knowledge and walks you through the basic commands in the browser.
The Introduction Series in the GitHub & Git Foundations video series is a collection of short, focused lessons, introducing the primary commands and workflows of git."


"One of the key features of my command line Git workflow is having the current Git context always displayed as part of the prompt. In particular, the prompt will display each of the following (depending on the current Git context):

Current branch name
Current commit hash
Indication of repo status (clean vs uncommitted changes)
This context is critical to my being able to confidently work with my repo, helping me to avoid common mistakes like committing to the wrong branch, forgetting to commit a specific file, etc.

The thoughtbot dotfiles contain a streamlined Git info segment, and my personal dotfiles contain a Git prompt configuration that includes the branch, current commit hash, and dirty status (note, this relies on some features of oh-my-zsh to display properly). Another option would be to use the excellent pure prompt for zsh which contains all this and more, but is still nice and snappy."

"Commits are a safety net, protecting you from any mishaps down the road. They're like save points in a video game and you can never have too many. Likewise, you can always reorder, combine, or even remove commits from your history if you want to clean it up later. Once you've made a commit, it's darn near impossible to lose that work without trying to.

I've never regretted making a commit, but I have regretted not making a commit. So, err on the side of caution and commit all the time!"