# Unifi-Video

This role installs or optionally updates Unifi-Video

## Requirements

- Python >= 2.6
- Debian or Ubuntu system (Unifi-Video does not support other distributions)

## Role Variables

### Required Fields:

    update_package: no

Set `update_package: yes` if it is desired for an existing installation to be updated to the latest version

# Example Playbook

    - hosts: nvr_host
      tasks:
        - name: Install Unifi-Video NVR Software
          include_role:
            name: unifi-video
          vars:
            update_package: yes


# TODO:

- None (Please suggest any ideas!)

# License

MIT

# Author Information

Created in 2017 by [Ben Dews](bendews.com)