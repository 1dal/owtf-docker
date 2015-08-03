## OWTF - Offensive Web Testing Framework

Official Docker image for [OWASP OWTF](http://owtf.org).

### Building the image:

*  Install **Docker**.(specific instructions can be found [here](https://docs.docker.com/installation/)).

*  Then run these commands, please notice that the first time these commands are run the script will download docker images from the registry,
   which might take a while depending on your internet connection.

   ```
   git clone https://github.com/owtf/owtf-docker.git

   ```

*  Run `docker build -t <yourpreferredname> <path to Dockerfile>`.

### Usage

*  You can launch your **OWTF** container by running `docker run -itd --privileged --net=host <image name>`.
   - `-d` launches the container as a *daemon*.
   - Get the image name by running `docker images`.

* Point your browser to `<hostip>:8009`.
