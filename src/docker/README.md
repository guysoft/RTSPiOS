Custom Pi OS with Docker
========================

Building a custom pi os within a docker environement will mean fewer changes to your host OS.

Creating the Docker image
-------------------------
Before building with Docker, you must build the custom_pios image.

```
cd <custom pios folder>/src
./build_docker
```

If you are told docker isn't running, make sure you have docker set up properly. You will need
docker running, and you will need to be in the `docker` group, or run with sudo. Running `docker ps`
is a good way to determine if it's configured for your use.

Building
--------
After you have the custom_pios image, you can execute run_docker_build.sh to build a custom pi os.
