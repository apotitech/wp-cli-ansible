# Ansible Role: WP-CLI


## Description

Ansible role for installing WP-CLI, a command line interface for WordPress.

## Installation

```bash
ansible-galaxy install melchilio.wp-cli
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| ```wp_cli_phar_url``` | ```https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar``` | Location of the WP-CLI phar to download |
| ```wp_cli_bin_path``` | ```/usr/bin/{{ wp_cli_bin_command }}``` | Location to store WP-CLI on remote machine |
| ```wp_cli_bin_command``` | wp | WP-CLI Coomand on remote machine |
| ```wp_cli_packages```  |  | List of WP-CLI packages for Installing |

## Dependencies

None

