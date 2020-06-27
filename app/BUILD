load("@rules_android//android:rules.bzl", "android_library")

android_binary(
    name="app_module",
    custom_package = "com.rahullohra.bazelandroid",
    srcs=["src/main/java/com/rahullohra/bazelandroid/MainActivity.java"],
    manifest="src/main/AndroidManifest.xml",
    resource_files=glob(["src/main/res/**"]),
    deps=[
        "@maven//:androidx_appcompat_appcompat",
        "@maven//:androidx_annotation_annotation",
        "@maven//:com_google_android_material_material",
        "@maven//:androidx_constraintlayout_constraintlayout",
#        "@maven//:androidx_navigation_navigation_fragment_ktx",
#        "@maven//:androidx_navigation_navigation_ui_ktx"
    ]
)

exports_files(["src/main/AndroidManifest.xml"])
exports_files(["src/main/java/com/rahullohra/bazelandroid/MainActivity.java"])