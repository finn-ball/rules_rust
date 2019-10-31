"""
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""
package(default_visibility = [
  # Public for visibility by "@raze__crate__version//" targets.
  #
  # Prefer access through "//wasm_bindgen/raze", which limits external
  # visibility to explicit Cargo.toml dependencies.
  "//visibility:public",
])

licenses([
  "notice", # "Apache-2.0"
])

load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_library",
    "rust_binary",
    "rust_test",
)


# Unsupported target "bench" with type "bench" omitted
# Unsupported target "hello-world" with type "example" omitted
# Unsupported target "input-tests" with type "test" omitted
# Unsupported target "network" with type "test" omitted
# Unsupported target "php-cgi" with type "example" omitted
# Unsupported target "readme-example" with type "example" omitted
# Unsupported target "serve-root" with type "example" omitted
# Unsupported target "simple-test" with type "test" omitted
# Unsupported target "ssl" with type "example" omitted

rust_library(
    name = "tiny_http",
    crate_root = "src/lib.rs",
    crate_type = "lib",
    edition = "2015",
    srcs = glob(["**/*.rs"]),
    deps = [
        "@raze__ascii__0_8_7//:ascii",
        "@raze__chrono__0_4_7//:chrono",
        "@raze__chunked_transfer__0_3_1//:chunked_transfer",
        "@raze__log__0_4_6//:log",
        "@raze__url__1_7_2//:url",
    ],
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "0.6.2",
    crate_features = [
        "default",
    ],
)

# Unsupported target "websockets" with type "example" omitted
