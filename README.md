# ansible-playbooks
## !!! THIS IS A WORK IN PROGRESS !!!
These are my personal Ansible playbooks to get up and running on fedora.
I wish someone would have made it just as easy for me when I switched from Windows to Linux.
I mainly use my PC for gaming and studying.

Feel free to use them as you see fit.

#### NOTE: you will need to comment/uncomment `#` which packages you want to install or not.
1. Install the [required packages](https://github.com/telometto/ansible-playbooks/blob/main/requirements.md)
2. Clone the repo.
3. Install Ansible.
4. Run the files you want with Ansible.

If you are *very* new, I will do a step-by-step under.

#### NOTE: omit the `$` and `#` at the start of each command. The `#` means that you have to use escalated privileges (aka `root`; i.e. `sudo`)

Open up a terminal and copy and paste each command, and hit enter (remember `root` where it is needed).
```
$ https://github.com/telometto/ansible-playbooks.git ~/your/desired/path
# dnf install -y ansible
# sudo su
$ cd /path/to/where/you/cloned/the/repo
```

Once you've done this, you can start executing the various plays. Need more instructions? See below.

Assuming that you want to execute the whole play:
```
# ansible-playbook tasks.yml
```

You may delete the files/folder after you are finished, if you wish to do so.

# USE COMMON SENSE AND ALWAYS INSPECT THE CONTENT OF THE FILES YOU ARE ABOUT TO EXECUTE.