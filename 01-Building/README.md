# Building a basic container

At this step, we attempt to build a container from scratch. To build a singularity container, you must use the `build` command.  The `build` command installs an OS, sets up your container's environment and installs the apps that are defined within the file.
To use the `build` command, we need a **recipe file**. A Singularity recipe file is a set of instructions telling Singularity what software to install within the container.
i

At this stage, its not possible to build Singularity containers using --build on the HPC as such the best way is to push
it to the Singularity hub and then pull it on the HPC.
