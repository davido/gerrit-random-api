load("//tools/bzl:plugin.bzl", "gerrit_plugin")

gerrit_plugin(
    name = "gerrit-random-api",
    srcs = glob(["java/**/*.java"]),
    manifest_entries = [
        "Gerrit-PluginName: gerrit-random-api",
        "Gerrit-ApiModule: com.googlesource.gerrit.plugins.random.ApiModule",
    ],
)
