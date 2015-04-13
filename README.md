playbook-ec2
============

My playbook for Amazon EC2.

## Roles

* common
* sshd
* zsh
* tmux
* emacs
* rvm
* nginx
* mysql
* postfix
* monit
* deploy

## Usage

	$ ansible-playbook --private-key ~/.ssh/aws/key.pem -u ec2-user -i hosts main.yml
