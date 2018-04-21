cc_library(
    name = "inotify-cxx",
    srcs = ["inotify-cxx.cpp"],
    hdrs = ["inotify-cxx.h"],
)

cc_binary(
    name = "example",
    srcs = ["example.cpp"],
    deps = [
        ":inotify-cxx",
    ],
)
