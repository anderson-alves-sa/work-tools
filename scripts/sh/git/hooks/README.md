# Git pre commit script for Java

This pre commit script runs a lint verification on the staged files of you git repository before your commit finishes and gives you the opportunity of aborting the commit or let it go.

# Files

* **pre-commit** - this file is the hook itself, and should be placed on the folder **.git/hooks** of your repository. It relies on a environment variable called **$CHECKSTYLE** that should point to a [CheckStyle](https://github.com/checkstyle/checkstyle) jar file. The example to set this variable is in the **.zshrc** file.
* **.zshrc** - just an example to set **$CHECKSTYLE** variable on your path.
