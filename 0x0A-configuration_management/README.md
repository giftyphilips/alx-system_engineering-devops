# Configuration management
Project to learn server configuration managementusing **Puppet** Obviously writing Puppet code for your infrastructure requires an investment of time and energy, but in the long term, it is for sure a must-have.

## Requirements :page_with_curl:
* All your files will be interpreted on Ubuntu 20.04 LTS
* All your files should end with a new line
* A README.md file at the root of the folder of the project is mandatory
* Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors
* Your Puppet manifests must run without error
* Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
* Your Puppet manifests files must end with the extension .pp

## Note on Versioning
* Install puppet
* Install puppet-lint

## Tasks :heavy_check_mark:

| Filename | Description |
| -------- | ----------- |
| `0-create_a_file.pp` | Create a file in `/tmp` |
| `1-install_a_package.pp` | Install `puppet-lint` |
| `2-execute_a_command.pp` | Create a manifest that kills a process named `killmenow` |
