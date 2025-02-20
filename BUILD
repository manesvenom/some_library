py_library(
    name = "some_code",
    srcs = ["src/some_code.py", "src/__init__.py"],
    imports = ["src"],
    visibility = ["//visibility:public"],
)

py_test(
    name = "some_code_test",
    srcs = ["test/some_code_test.py"],
    deps = [":some_code"],
)