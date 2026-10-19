
# My Nginx Web Server 🌐

This was one of my first hands-on Linux and DevOps projects. I wanted to understand how a web server works, so I installed Nginx on Ubuntu and used it to serve my own simple HTML webpage.

It helped me get comfortable with Linux services, terminal commands, and testing a website locally.

## What I worked on

- Installed Nginx using Ubuntu's package manager.
- Created a custom HTML webpage.
- Configured Nginx to serve my page locally.
- Started and checked the Nginx service using `systemctl`.
- Enabled Nginx to start automatically when Ubuntu boots.
- Tested the configuration with `nginx -t`.
- Checked the HTTP response using `curl`.
- Uploaded the project to GitHub.

## Tools I used

- Ubuntu Linux
- Nginx
- HTML
- Linux terminal
- Git and GitHub

## Project files

```text
nginx-web-server/
├── index.html
└── README.md
```

## How to run it

First, install Nginx on Ubuntu:

```bash
sudo apt update
sudo apt install nginx
```

Start Nginx and enable it at startup:

```bash
sudo systemctl enable --now nginx
```

Copy the webpage from this project into Nginx's web directory:

```bash
sudo cp index.html /var/www/html/index.html
```

Check that the Nginx configuration is valid:

```bash
sudo nginx -t
```

Then open `http://localhost` in your browser.

You can also check the response from your terminal:

```bash
curl http://localhost
```

## What I learned

This project gave me practical experience with installing software on Linux, managing services, serving HTML pages, and checking whether a web server is working correctly.

I'm using projects like this to build my Linux fundamentals before moving into more advanced DevOps tools and workflows.

## Author

**Taaha Mustafa Khan**

GitHub: https://github.com/taahakhan-stack
