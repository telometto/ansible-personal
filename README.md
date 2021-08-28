# ansible
## !!! THIS IS A WORK IN PROGRESS !!!
These are my personal Ansible playbooks to get up and running on fedora.
I wish someone would have made it just as easy for me when I switched from Windows to Linux.
I mainly use my PC for gaming and studying.

Feel free to use them as you see fit.

#### NOTE: you will need to comment/uncomment `#` which packages you want to install or not! This is done by either deleting files in the 'tasks' folder or by commenting the tasks in the 'main.yml' file in the 'roles' folder(s).
1. Install the [required packages](https://github.com/telometto/ansible/wiki/Requirements)
2. Clone the repo.
3. Run 'site.yml'.

If you are *very* new, I will do a step-by-step under.

#### NOTE: omit the `$` and `#` at the start of each command. The `#` means that you have to use escalated privileges (aka `root`; i.e. `sudo`)

Open up a terminal and copy and paste each command, and hit enter.

Follow the [installation instructions in the wiki](https://github.com/telometto/ansible/wiki/Requirements)
```
$ https://github.com/telometto/ansible-playbooks.git ~/your/desired/path
$ cd /path/to/where/you/cloned/the/repo
$ ansible-playbook --ask-become-pass site.yml
```
>When asked for the `BECOME` pass, enter the user password.

Once you've done this, you can start executing the various plays. Need more instructions? See below.

You may delete the files/folder after you are finished, if you wish to do so.

# USE COMMON SENSE AND ALWAYS INSPECT THE CONTENT OF THE FILES YOU ARE ABOUT TO EXECUTE.