load("//tools:argcv_archive.bzl", "argcv_archive")

argcv_archive(
  name = "com_github_argcv_argcv",
  sha256 = "",
  git_commit = "7f8d399f8bbb424a3e8249eec427ab9b82601ccd",
)

load("@com_github_argcv_argcv//tools:version.bzl", "check_version")

check_version("0.4.3")

load("@com_github_argcv_argcv//tools:argcv.bzl", "argcv_deps")
argcv_deps()
