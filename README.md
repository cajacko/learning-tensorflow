# Learning TensorFlow

Make sure Docker is installed on your system. Then run `./docker.sh`
(linux/MacOS only). This will download the docker image, needed to run
tensorflow and will open up bash inside the container.

From here navigate to /tensorflow. This directory will contain everything in
this repo, as a shared volumne. So all changes you make on your host machine
will be reflected in the container.

To run an example you can run `python ./01/test.py`.
