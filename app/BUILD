load("@rules_android//android:rules.bzl", "android_library")

android_binary(
    name = "app_module",
    srcs = ["src/main/java/com/rahullohra/bazelandroid/MainActivity.java"],
    custom_package = "com.rahullohra.bazelandroid",
    manifest = "src/main/AndroidManifest.xml",
    manifest_values = {
        "minSdkVersion": "21",
    },
    resource_files = glob(["src/main/res/**"]),
    deps = [
        "@maven//:androidx_appcompat_appcompat",
        "@maven//:androidx_annotation_annotation",
        "@maven//:com_google_android_material_material",
        "@maven//:androidx_constraintlayout_constraintlayout",
        #        "@maven//:androidx_navigation_navigation_fragment_ktx",
        #        "@maven//:androidx_navigation_navigation_ui_ktx",
        "//mylibrary",
    ],
)

exports_files(["src/main/AndroidManifest.xml"])

exports_files(["src/main/java/com/rahullohra/bazelandroid/MainActivity.java"])
