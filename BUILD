load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "gazelle")

go_prefix("https://github.com/pierre-leblanc/testing-bazel-go")

# bazel rule definition
gazelle(
  prefix = "https://github.com/pierre-leblanc/testing-bazel-go",
  name = "gazelle",
  command = "fix",
)
