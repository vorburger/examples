How to use this example
=======================

As per https://docs.bazel.build/versions/master/generate-workspace.html :

    pushd . ; cd ../.. ; git clone https://github.com/bazelbuild/migration-tooling.git ; bazel run //generate_workspace ; popd
    java -jar ../../migration-tooling/transitive_maven_jar/generate_workspace_deploy.jar -m . -o . --direct-to-ws

    TODO bazel build ...
