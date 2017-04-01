go_prefix("github.com/q231950/bzlexp")

go_library(
      name = "go_default_library",
      srcs = ["main.go"],
      visibility = ["//visibility:private"],
      deps = ["//cmd:go_default_library"],
)

go_binary(
      name = "bzlexp",
      library = ":go_default_library",
      visibility = ["//visibility:public"],
)
