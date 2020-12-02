## Configuration

This doc has an easy config for new equipment work (Linux / Mac )

### Requirements
- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- Linux or mac (S.O.)
- [Composer](https://getcomposer.org/)
- [Oh my Zsh](https://ohmyz.sh/)

### Add Commands (globally)
Edit your file `$PWD/.zshrc`

``` text
# Composer export PATH="$PATH:$HOME/.composer/vendor/bin"
# This line active the commands for execute dbs
export PATH=$PATH:path_download_repository/configuration/commands/db
```

### How run commands for db
For the moment a unique command execute the architecture postgres and mysql,
for  projects with these specifications.

``` shell script
$ active_dbs
```

### How run commands for start linux server with docker and docker-compose
This command install docker and docker-compose

``` shell script
$ server_init_linux
```
