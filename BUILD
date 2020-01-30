load("@bazel_tools//tools/build_defs/pkg:pkg.bzl", "pkg_tar")

cc_library(
    name = "fmt",
    srcs = glob([
        "src/**/*.cpp",
    ]),
    hdrs = glob([
        "include/**/*.h",
        "include/**/*.inl",
    ]),
    strip_include_prefix = "include",
    deps = [
        "@boost//:headers",
    ],
    visibility = ["//visibility:public"],
)
