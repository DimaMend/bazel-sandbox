
load("//build_tools/py:py.bzl", "dbx_py_pypi_piplib")

dbx_py_pypi_piplib(
    name = "pyTenable",
    pip_version = "1.4.22",
    provides = [
        "tenable",
        "tenable.io",
        "tenable.sc",
    ],
    deps = [
        "//pip/defusedxml",
        "//pip/marshmallow",
        "//pip/python-box",
        "//pip/python-dateutil",
        "//pip/requests",
        "//pip/restfly",
        "//pip/semver",
        "//pip/typing_extensions",
        "//pip/urllib3",
    ],
)}