# gfab

*Work in progress*

Project goal: A package that can generate server deploy scripts with custom options for different stacks and environments.

Never write shitty deploy scripts again. Generated scripts will include various built-in safety features such as confirmation prompts, dry-run options, human-friendly messages, etc.

### Supported platforms

Local: Starting with OSX, eventually Windows and Ubuntu

Remote: Starting with AWS EC2 with Ubuntu 16.04, possibly more in the future.

### Planned features

*This is not a complete list*

* git deploy
* nginx (with auto config based on upstream/proxy/etc)
* PHP-FPM 7
* node.js
* S3
* Redis
* MySQL
* And many more features for both local setup and bootstrapping remote servers
