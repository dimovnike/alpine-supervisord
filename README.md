## Simple supervisord container based on alpine linux.

The supervisord is setup as the entrypoint of the container and is condfigured to load configs from /etc/supervisor/conf.d/.

The purpose of this image is to be extended and have multiple processes in a single container. To do this, add configs to /etc/supervisor/conf.d/. Each layer can have its own processes.
