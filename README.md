# Simple Robot Navigation

Using ROS 2 and Gazebo to demonstrate motion planning algorithms in drones.

## Small things worth saying
1. Don't try using docker containers to get ROS 2 working on macOS. Instead, use vmWare Fusion with an [arm64 Ubuntu 24.04 iso file](https://cdimage.ubuntu.com/daily-live/20240421/noble-desktop-arm64.iso). I spent 15 hours dealing with X11 forwarding/VNC issues before giving up. Use link to find the iso file, I had trouble finding it with google. 
2. The `/opt/ros/<distro>/setup.bash` modifies `PYTHONPATH` environment variable. Use VSCode's ROS extension command "Update Python Path" for language server support.

