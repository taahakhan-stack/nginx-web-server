# Nginx Web Server on Ubuntu

## Overview
Installed and configured Nginx on Ubuntu Linux
to serve a custom HTML webpage locally.

## What I Learned
- Installing software with apt
- Managing services with systemctl
- Enabling services at startup
- Creating a webpage using HTML
- Testing Nginx configuration with nginx -t
- Testing HTTP responses with curl

## Technologies
- Ubuntu Linux
- Nginx
- HTML
- Bash terminal
- Git and GitHub

## How to Test
Open http://localhost in a browser.

Check the service:
sudo systemctl status nginx

Test the configuration:
sudo nginx -t

Test the HTTP response:
curl http://localhost

