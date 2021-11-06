load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

git_repository(
    name = "bazel_skylib",
    commit = "f80bc733d4b9f83d427ce3442be2e07427b2cc8d",
    remote = "git@gitlab.tableausoftware.com:tableaubuild/bazel/mirrors/bazel/bazel-skylib.git",
    shallow_since = "1611945497 -0500",
)

git_repository(
    name = "rules_python",
    remote = "git@gitlab.tableausoftware.com:tableaubuild/bazel/mirrors/bazel/rules_python.git",
    commit = "a0fbf98d4e3a232144df4d0d80b577c7a693b570", # https://github.com/bazelbuild/rules_python/releases/tag/0.0.2
    shallow_since = "1586444447 +0200",
)

git_repository(
    name = "com_google_protobuf",
    commit = "7c40b2df1fdf6f414c1c18c789715a9c948a0725",  # v3.19.1
    remote = "https://github.com/protocolbuffers/protobuf.git",
    shallow_since = "1635455273 -0700",
)

http_archive(
    name = "rules_proto",
    sha256 = "66bfdf8782796239d3875d37e7de19b1d94301e8972b3cbd2446b332429b4df1",
    strip_prefix = "rules_proto-4.0.0",
    url = "https://github.com/bazelbuild/rules_proto/archive/refs/tags/4.0.0.tar.gz",
)
