# bazel-hw-6sense
Building Python package using Bazel.
This repository is used to create Hello World executable package using the Bazel build system.

Installing Bazel Wrapper:

Download the bazel wrapper from Bazel Github page(Choose the package based on your OS): https://github.com/bazelbuild/bazelisk/releases
Rename the .exe package to bazel.exe and add the PATH to your Environment.
Test bazel by running the "bazel" commnad on terminal/CMD.
Clone and Build the package with Bazel:

Clone the "bazel-6sense" repository to your local and CD to the repository(directory)
Execute "bazel build //hello-world:hello-world" to build the package.
All the output packages will generated and stored in our current repository directory.
Results will be available in /bazel-bin/hello-world (hello-world.exe and hello-world.zip)
For reference "results" directory is addded to the repository with executables package.
