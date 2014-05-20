# Overview

This is an ansible playbook for deploying [Sentry](http://getsentry.com ) on
Ubuntu 14.04.

# Usage

Change the vars file (roles/sentry/vars/main.yml) as appropriate, create an
inventory file, then run:

	ansible-playbook -i your.inventory deploy.yml

