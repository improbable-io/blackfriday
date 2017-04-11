load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_prefix", "go_test")

go_prefix("github.com/russross/blackfriday")

go_library(
    name = "go_default_library",
    srcs = [
        "block.go",
        "html.go",
        "inline.go",
        "latex.go",
        "markdown.go",
        "smartypants.go",
    ],
    visibility = ["//visibility:public"],
    deps = ["@com_github_shurcooL_sanitized_anchor_name//:go_default_library"],
)
