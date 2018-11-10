# Ansible Role: raspberrypi-docker

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    # The default install script url
    script_url: https://get.docker.com

## Dependencies

None.

## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: raspberrypi-docker