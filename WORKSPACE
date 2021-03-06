# Copyright 2016 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

workspace(name = "copybara")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("//third_party:bazel.bzl", "bazel_version")

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "guava",
    artifact = "com.google.guava:guava:27.0.1-jre",
    sha1 = "bd41a290787b5301e63929676d792c507bbc00ae",
)

maven_jar(
    name = "failureaccess",
    artifact = "com.google.guava:failureaccess:1.0.1",
    sha1 = "1dcf1de382a0bf95a3d8b0849546c88bac1292c9",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "guava_testlib",
    artifact = "com.google.guava:guava-testlib:27.0.1-jre",
    sha1 = "97247f5b2229f6e23bea40f4c9668546cc8b38dd",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "autocommon",
    artifact = "com.google.auto:auto-common:0.10",
    sha1 = "c8f153ebe04a17183480ab4016098055fb474364",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "autovalue",
    artifact = "com.google.auto.value:auto-value:1.6.3",
    sha1 = "8edb6675b9c09ffdcc19937428e7ef1e3d066e12",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "autovalueannotations",
    artifact = "com.google.auto.value:auto-value-annotations:1.6.3",
    sha1 = "b88c1bb7f149f6d2cc03898359283e57b08f39cc",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "jcommander",
    artifact = "com.beust:jcommander:1.48",
    sha1 = "bfcb96281ea3b59d626704f74bc6d625ff51cbce",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "truth",
    artifact = "com.google.truth:truth:0.42",
    sha1 = "b5768f644b114e6cf5c3962c2ebcb072f788dcbb",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "diffutils",
    artifact = "com.googlecode.java-diff-utils:diffutils:1.3.0",
    sha1 = "7e060dd5b19431e6d198e91ff670644372f60fbd",
)

# LICENSE: The Apache Software License, Version 2.0
# Required by mockito
maven_jar(
    name = "objenesis",
    artifact = "org.objenesis:objenesis:1.0",
    sha1 = "9b473564e792c2bdf1449da1f0b1b5bff9805704",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "mockito",
    artifact = "org.mockito:mockito-core:1.9.5",
    sha1 = "c3264abeea62c4d2f367e21484fbb40c7e256393",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "jimfs",
    artifact = "com.google.jimfs:jimfs:1.1",
    sha1 = "8fbd0579dc68aba6186935cc1bee21d2f3e7ec1c",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "jsr305",
    artifact = "com.google.code.findbugs:jsr305:3.0.2",
    sha1 = "25ea2e8b0c338a877313bd4672d3fe056ea78f0d",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "google_http_client",
    artifact = "com.google.http-client:google-http-client:jar:1.27.0",
    sha1 = "52d6076f58edfedb55526c0cac4ba155c6dc645b",
)

# LICENSE: The Apache Software License, Version 2.0
# TODO(malcon): google http client needs this in 1.27.0, but the dependency
# has been removed at HEAD. Remove once version is updated.
maven_jar(
    name = "commonscodec",
    artifact = "commons-codec:commons-codec:jar:1.11",
    sha1 = "3acb4705652e16236558f0f4f2192cc33c3bd189",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "google_http_client_test",
    artifact = "com.google.http-client:google-http-client-test:jar:1.27.0",
    sha1 = "f0a9872c855d4282183ae8a2685cd74b269d99f1",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "google_http_client_gson",
    artifact = "com.google.http-client:google-http-client-gson:jar:1.27.0",
    sha1 = "fdb0bbb9b5d2361ec317a7ded040552e2ad7fe76",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "gson",
    artifact = "com.google.code.gson:gson:jar:2.8.5",
    sha1 = "f645ed69d595b24d4cf8b3fbb64cc505bede8829",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "flogger",
    artifact = "com.google.flogger:flogger:0.3.1",
    sha1 = "585030fe1ec709760cbef997a459729fb965df0e",
)

# LICENSE: The Apache Software License, Version 2.0
maven_jar(
    name = "flogger_system_backend",
    artifact = "com.google.flogger:flogger-system-backend:0.3.1",
    sha1 = "287b569d76abcd82f9de87fe41829fbc7ebd8ac9",
)

# LICENSE: Common Public License 1.0
maven_jar(
    name = "junit",
    artifact = "junit:junit:4.11",
    sha1 = "4e031bb61df09069aeb2bffb4019e7a5034a4ee0",
)

# LICENSE: The Apache Software License, Version 2.0
http_archive(
    name = "io_bazel",
    url = "https://github.com/bazelbuild/bazel/archive/" + bazel_version + ".zip",
    strip_prefix = "bazel-" + bazel_version,
)

http_archive(
    name = "com_google_protobuf",
    url = "https://github.com/bazelbuild/bazel/archive/" + bazel_version + ".zip",
    strip_prefix = "bazel-" + bazel_version + "/third_party/protobuf/3.6.1",
)

# LICENSE: New BSD
maven_jar(
    name = "re2j",
    artifact = "com.google.re2j:re2j:1.2",
    sha1 = "4361eed4abe6f84d982cbb26749825f285996dd2",
)
