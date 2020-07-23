# hugo_in_docker
It is currently used only as utility for containers build with https://github.com/rgr19/hugo_with_proxy_and_maintainer_in_docker_compose

Two modes to run Makefile:

- make : BUNDLED MODE is used by above mentioned project
- make docker : STANDALONE MODE is used to run hugo in docker in standalone mode

As I remember, I'm calling make from make when inside container to load env variables properly.
