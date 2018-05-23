package(default_visibility = ["//visibility:public"])

licenses(["notice"])

cc_library(
    name="xapian_core",
    hdrs = glob(
        ["**/*.h"],
        exclude = [
            "bin/**/*.h", 
            "tests/**/*.h",
            "examples/**/*.h",
            "common/safewindows.h",
            "common/win32_uuid.h"
        ]
    ),
    srcs = glob(
        ["**/*.cc"],
        exclude = [
            "bin/**/*.cc", 
            "tests/**/*.cc",
            "examples/**/*.cc",
            "include/xapian/version_h.cc",
            "common/win32_uuid.cc",
        ]
    ),
    includes = [
        "include",
        "common",
        "genfiles",
    ],
)
