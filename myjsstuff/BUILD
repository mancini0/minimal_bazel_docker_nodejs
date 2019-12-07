load("@io_bazel_rules_docker//nodejs:image.bzl", "nodejs_image")
load("@npm_bazel_typescript//:index.bzl", "ts_library")

ts_library(
    name = "greeter",
    srcs = ["Greeter.ts"],
)

nodejs_image(
    name = "app",
    data = [
        #your homework is to figure out how to import the greeter ts library into your js app :)
        #        ":greeter",
    ],
    entry_point = "App.js",
)
