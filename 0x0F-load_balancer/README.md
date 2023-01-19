# Load Balancer
For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements.

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs
* All your files will be interpreted on Ubuntu 16.04 LTS
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* All your Bash script files must be executable
* Your Bash script must pass Shellcheck (version 0.3.7) without any error
* The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing

## Tasks :heavy_check_mark:

---
### [0. Double the number of webservers](./0-custom_http_response-header)
* In this first task you need to configure web-02 to be identical to web-01. Fortunately, you built a Bash script during your web server project, and they’ll now come in handy to easily configure web-02. Remember, always try to automate your work!

### [1. Install your load balancer](./1-install_load_balancer)
* Install and configure HAproxy on your lb-01 server.

### [2. Add a custom HTTP header with Puppet](./2-puppet_custom_http_response_header.pp)
* Just as in task #0, we’d like you to automate the task of creating a custom HTTP header response, but with Puppet
---
