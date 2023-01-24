# 0x10-https_ssl
Project on What happens when you don’t secure your website traffic?
Concepts learnt:
- What is HTTPS SSL 2 main roles
- What is the purpose encrypting traffic
- What SSL termination means

## Requirements :page_with_curl:
- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Task :heavy_check_mark:
### 0. World wide web
- Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01). Let’s also add other subdomains to make our life easier, and write a Bash script that will display information about subdomains.

### 1. HAproxy SSL termination
- “Terminating SSL on HAproxy” means that HAproxy is configured to handle encrypted traffic, unencrypt it and pass it on to its destination.
- Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www.

### 2. No loophole in your website traffic
- A good habit is to enforce HTTPS traffic so that no unencrypted traffic is possible. Configure HAproxy to automatically redirect HTTP traffic to HTTPS.
