# Simple Robot Navigation
Using PX4-Autopilot to demonstrate motion planning algorithms in a drone.

## Installing PX4-Autopilot
I'm using an amd64 Ubuntu 22.04 Lenovo Thinkpad X1 to do this experiment. I'm using the v1.14.0 of PX4-Autopilot.

```bash
git clone git clone https://github.com/PX4/PX4-Autopilot.git
git fetch --all --tags
git checkout test v1.14.0
. ./Tools/setup/ubuntu.sh
make px4_sitl gz_x500
```

#### Notes

1. The first time that I ran the px4_sitl command, my terminal instantly exited. I booted up again, and then the build system ran successfully. Please let me know if any of you can replicate this.
2. I originally tried this on macOS, but had trouble with setup because gazebo classic doesn't work well in that environment. I had tried docker containers as well as a VM.

## Contact Info
If you have any issues getting this setup, PLEASE let me know. I would be happy to help you and get this started.

aksgula22@gmail.com
