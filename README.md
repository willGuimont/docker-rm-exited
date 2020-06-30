# docker-rm-exited
Remove exited docker containers

# Installation

Need to be able to run docker commands without `sudo`, see [documentation](https://docs.docker.com/engine/install/linux-postinstall/)

1. `mkdir ~/bin`
2. Copy docker-rm-exited into `~/bin`
3. `chmod +x ~/bin/docker-rm-exited`
4. Add `PATH=$PATH:$HOME/bin` at the end of your `~/.bashrc`
5. Use with `docker-rm-exited`
