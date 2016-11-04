# Usage

Use this repository to store:

1.	Source code
2.	Ansible playbooks/roles/configs/inventories
3.	Vagrantfiles
4.	Dockerfiles
5.	Any other stuff supporting our app 

# Rules

Rule of usage are:

1.	No binaries in git (use .gitignore to – well – ignore them)
2.	If there is a need for binaries, use a text file referencing them online. (for example: ref_jenkinswar.txt)
3.	Work on your branch, and your branch only! (each should have its own dev-<name> branch)
4.	The Repo Master will aggregate/merge each finished task into the “master” branch, when necessary.

# Configure git

Follow these steps to configure your git:

1.	Please go to http://git.endava.com and log-in once with your Endava credentials. This step is very important!
2.	Notify the Team Leader (master role) after you did this, so that he can add you to the git repository members.
3.	The Master of the repository will add you with "Developer" rights.
4.	Please generate a public-private SSH key-pair on your local computer or locate the public key, if you already have done that.
5.	Send the public key by email to the repository Master. IMPORTANT: Keep your private key SAFE and private!
6.	From the command line (of your "controller" machine, for example), configure the following Global Configs for git:

```sh
    $ git config --global user.name "John Doe"
    $ git config --global user.email johndoe@example.com
```

> NOTE: Replace "John Doe" above with your name and "johndoe@example.com" with your Endava email.

7.	Go to the folder that you will need to clone the repository into (for example, your "/home/vagrant" folder on the "controller" computer)

8.	Clone the remote repository with the following command;
```sh
    $ git clone git@git.endava.net:Endava/ama-cdp4jwa.git
```

> NOTE: Even if the repository is publicly advertised as  git@git.endava.com:Endava/ama-cdp4jwa.git, always make sure to replace .com with .net, otherwise it won't work.

# Git cheatsheet
You can find a git cheatsheet here:

[Git Cheatsheet](https://services.github.com/kit/downloads/github-git-cheat-sheet.pdf)