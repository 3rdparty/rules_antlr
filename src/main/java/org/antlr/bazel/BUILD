load("@rules_java//java:defs.bzl", "java_binary")

package(default_visibility = ["//visibility:public"])

filegroup(
    name = "srcs",
    srcs = glob(["*"]),
)

java_binary(
    name = "bazel",
    srcs = glob(["*.java"]),
    main_class = "org.antlr.bazel.AntlrRules",
)
