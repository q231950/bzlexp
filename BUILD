load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_binary")

go_prefix("github.com/q231950/bzlexp")

go_binary(
    name = "hello",
    srcs = ["main.go"],
    deps = ["//lib:go_default_library"]
)
