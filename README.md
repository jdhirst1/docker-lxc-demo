This is just a proof of concept. It shows that it is possible to run a stateful lxc within a (privileged) docker container.

Further development will be done in https://github.com/micw/docker-lxc


Todos:
* shutdown signal handler that gracfully stops the lxc container on docker stop
* check if it's possible to run in an unprivileged container
* customize the lxc container using env vars and vagrant provisioners
* use and document volumes to persist the lxc container independent docker container
