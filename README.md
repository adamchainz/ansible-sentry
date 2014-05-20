# Overview

This is an ansible playbook for deploying [Sentry](http://getsentry.com ) on
Ubuntu 14.04.

# Usage

Create an inventory file, set the vars (either in the vars file
`roles/sentry/vars/main.yml` or in your inventory), then run:

	ansible-playbook -i your.inventory deploy.yml

