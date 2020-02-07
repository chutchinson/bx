cc_library(
    name = "bx",
    visibility = ["//visibility:public"],
    srcs = [
        "src/allocator.cpp",
        "src/bx.cpp",
        "src/bx_p.h",
        "src/commandline.cpp",
        "src/crtnone.cpp",
        "src/debug.cpp",
        "src/dtoa.cpp",
        "src/easing.cpp",
        "src/file.cpp",
        "src/filepath.cpp",
        "src/hash.cpp",
        "src/math.cpp",
        "src/mutex.cpp",
        "src/os.cpp",
        "src/process.cpp",
        "src/semaphore.cpp",
        "src/settings.cpp",
        "src/sort.cpp",
        "src/string.cpp",
        "src/thread.cpp",
        "src/timer.cpp",
        "src/url.cpp"
    ],
    hdrs = glob([
        "include/**/*.h"
    ]),
    includes = [
        "3rdparty",
        "include",
        "include/compat/msvc"
    ],
    local_defines = [
        "__STDC_LIMIT_MACROS",
		"__STDC_FORMAT_MACROS",
		"__STDC_CONSTANT_MACROS"
    ]
)