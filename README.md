this is a simple test to see whether bazel can interop with gradle
```
bazel build src/main/java/gradle/bazel/tests:App
cp bazel-bin/src/main/java/gradle/bazel/test/App.jar libs
./gradlew :test
```
