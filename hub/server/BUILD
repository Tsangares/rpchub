cc_library(
    name = "server",
    srcs = glob(["**/*.cc"]),
    hdrs = glob(["**/*.h"]),
    visibility = ["//visibility:public"],
    deps = [
        "//common",
        "//common/crypto",
        "//common/stats",
        "//hub/auth",
        "//hub/auth:dummy_provider",
        "//hub/auth:hmac_provider",
        "//hub/commands",
        "//hub/crypto:signing",
        "//hub/db",
        "//hub/iota:local_pow",
        "//hub/iota:pow",
        "//hub/iota:remote_pow",
        "//hub/service:attachment_service",
        "//hub/service:sweep_service",
        "//hub/service:user_address_monitor",
        "//proto:hub_grpc_cc",
        "@boost//:property_tree",
        "@com_github_google_glog//:glog",
        "@org_iota_entangled//cppclient:beast",
    ],
)
