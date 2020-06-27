load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_android_library")

kt_android_library(
    name = "mylibrary",
    #    srcs = glob(["src/main/java/**/*.kt"]),
    srcs = glob(["src/main/java/com/rahullohra/mylibrary/Apple.kt"]),
    custom_package = "com.rahullohra.mylibrary",
    manifest = "src/main/AndroidManifest.xml",
    visibility = ["//visibility:public"],
    deps = [
        "@maven//:androidx_appcompat_appcompat",
        "@maven//:io_reactivex_rxjava2_rxjava",
    ],
)
