
# Dependency check action

This action uses the docker image built every night in [link to build repo]. This image includes the updated vulnerabilities database so there is no need to update it. Therefore, it speeds up the test.

By now, the action receives three parameters. Project name, scanpath and report format, but more parameters can be added as optional


