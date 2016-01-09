# Ansible Role: WP-CLI

## Description

Ansible role for installing WP-CLI, a command line interface for WordPress.

## Installation

```
$ ansible-galaxy install sbaerlocher.wp-cli
```

## Requirements

None

## Role Variables

All available variables and default values are listed below. You may override these in your Playbook, `group_vars`, command line etc.

```yml
wp_cli_phar_url: https://raw.github.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
```

Location of the WP-CLI phar to download.

```yml
wp_cli_bin_path: /usr/bin/wp
```

Location to store WP-CLI on remote machine.

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.wp-cli
```

## Changelog

### 1.0

* Initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2016, Simon Bärlocher