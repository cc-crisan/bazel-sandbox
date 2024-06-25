
load("@bazel_skylib//:workspace.bzl", "bazel_skylib_workspace")

bazel_skylib_workspace()

load("@rules_python//python:repositories.bzl", "python_register_toolchains", "py_repositories")

py_repositories()


# python_register_toolchains(
#     name = "python3_10",
#     python_version = "3.10",
#     ignore_root_user_error = True
# )

# load("@python3_10//:defs.bzl", "interpreter")

# load("@rules_python//python:pip.bzl", "pip_parse")

# pip_parse(
#     python_interpreter_target = interpreter,
# )
