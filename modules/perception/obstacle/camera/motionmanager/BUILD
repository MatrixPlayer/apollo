load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "motionmanager",
    srcs = [
        "vehicleplanemotion.cc",
    ],
    hdrs = [
        "vehicleplanemotion.h",
    ],
    copts = [
        "-Wno-deprecated",
    ],
    deps = [
        "//modules/perception/obstacle/base",
    ],
)

cpplint()
