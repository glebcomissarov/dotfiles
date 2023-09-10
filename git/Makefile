SHELL := /bin/bash

# Set name and email for project
local_setup:
	git config --local user.name "Gleb K" && \
		git config --local user.email ""

# Use specific ssh key file for "git push" command
# It will be usfull if you have multiple GitHub accounts
add_ssh_file:
	git config --local core.sshCommand "/usr/bin/ssh -i ~/.ssh/my_rsa"
