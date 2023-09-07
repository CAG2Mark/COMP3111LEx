# COMP3111LEx
I am going to use this README as an opportunity to point out all the problems with this lab and why it is poorly designed.
1. Don't push `.idea` or other project settings... different people use different IDEs like IntelliJ IDEA, Eclipse, VSCode, or even neovim with some plugins... they may also have different preferences and system-specific things that will break if you share project settings.
2. Don't push `target` because it just pollutes the repository with stuff that is non-essential to running the code. Use CI if you really want to share binaries.
3. Naming conventions please... classes should be PascalCased, and parameters should be snakeCased.
