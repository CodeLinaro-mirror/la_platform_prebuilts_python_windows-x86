package(default_visibility = ["//visibility:public"])

filegroup(
    name = "windows-x86",
    srcs = glob(
        include = ["**"],
        exclude = [
            ".git/**",
            "**/*.pyc",
        ],
    ),
)

filegroup(
    name = "windows-x86-bundle",
    srcs = glob(
        include = [
            "x64/Lib/**",
            "x64/DLLs/**",
        ],
        exclude = [
            "**/*.pyc",
            "x64/Lib/test/**",
            "x64/Lib/unittest/**",
            "x64/Lib/config/**",
            "x64/Lib/distutils/**",
            "x64/Lib/idlelib/**",
            "x64/Lib/lib2to3/**",
            "x64/Lib/plat-linux2/**",
            "x64/Lib/bsddb/test/**",
            "x64/Lib/ctypes/test/**",
            "x64/Lib/email/test/**",
            "x64/Lib/lib-tk/test/**",
            "x64/Lib/sqlite3/test/**",
        ],
    ),
)
