# Build commands

bazel build //...
bazel run //main:main

bazel build //... -s
bazel build //... -s --copt=-O0

bazel clean
