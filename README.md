# RepoSsessed

RepoSsessed is a project designed to parse public source code repositories and find various types of vulnerabilities. 

- Coding flaws that lead to critical vulnerabilities
- Hardcoded passwords
- Sensitive configuration files
- Database connection strings
- Private SSL keys
- Private SSH keys
- Uploaded Unix/Linux home directories, with sensitive dotfiles
- <code>~/.ssh</code> directories full of keys
- Source code of projects you're currently doing blackbox testing on
- Etc...

## Philosophy

Finding flaws in public source code repositories is not a new idea, and many have done great work in the area.

The reason this project was created was twofold:

1. To add **source code flaws** to the public source code repository conversation. So, not just looking for information disclosure, but actual coding flaws as well, e.g., input validation mistakes that can lead to critical bugs in various languages. 
2. I am looking to **collapse all useful code repository signatures, including my own for coding flaws, into a single, flat, transparent format that can be used by ANY engine**. This way you can write whatever interface you'd like and use the evergreen signatures from this project.

## Credits

I'd like to give credit to the following people for either their prior work or their contributions:

- Samar Dhwoj Acharya for allowing me to use signatures from his Github Dorks project
- Michael Henriksen for allowing me to use signature files from his GitRob project
