The Open Dynamics Engine with Threading Building Blocks (ODE-TBB)
-----------------------------------------------------------------

This is the ODE-TBB fork of the Open Dynamics Engine. ODE is a free,
industrial quality library for simulating articulated rigid body
dynamics - for example ground vehicles, legged creatures, and moving
objects in VR environments. It is fast, flexible, robust and platform
independent, with advanced joints, contact with friction, and built-in
collision detection. Intel's Threading Building Blocks (TBB) is a
widely used C++ template library for task parallelism.

Please refer to the README.txt file for the original ODE
documentation; installation and usage is the same as described in that
file, and in the resources referenced therein, with one exception: you
should probably run `configure` with the `--enable-malloc` flag, to
prevent running out of memory when many threads are created.