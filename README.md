# DockerWebAppWithDebugOverride

An example app that demonstrates how to override settings in the Docker compose file when using Visual Studio.

https://docs.microsoft.com/en-us/visualstudio/containers/docker-compose-properties?view=vs-2019#docker-compose-file-labels

Note that Visual Studio will perform optimizations when debugging containers. One of these optimizations is the `Fast mode` option.
> In Fast mode, Visual Studio calls docker build with an argument that tells Docker to build only the base stage.

https://docs.microsoft.com/en-us/visualstudio/containers/container-build?view=vs-2019#debugging
