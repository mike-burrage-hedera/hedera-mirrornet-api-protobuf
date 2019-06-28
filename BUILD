proto_library(
    name = "proto",
    srcs = glob(["src/main/proto/*.proto"]),
    deps = glob(["@hapi//:*.proto"]) + ["@com_google_protobuf//:google/protobuf/wrappers.proto"],
)

java_proto_library(
    name = "java_proto",
    deps = [":proto"],
)
