java_binary (
    name = "BazelApp",
    srcs = glob(["java/**/*.java"]),
    main_class = "example.Main",
    deps = [
        "@maven//:org_slf4j_slf4j_api",
        "@maven//:org_slf4j_slf4j_log4j12",
        "@maven//:org_projectlombok_lombok",
        "@maven//:org_apache_commons_commons_lang3",
        "@maven//:org_webjars_bootstrap",
        "@maven//:com_bladejava_blade_mvc"
    ],
    visibility = ["//visibility:public"],
)
