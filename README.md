# Install sdkman

```bash
curl -s "https://get.sdkman.io" | bash
```

Install java graalvm

```bash
sdk install java 22-graalce
```

install the build tool ubuntu 22.04

```bash
sudo apt-get install build-essential zlib1g-de
```

Clone the repo, compile to native and run

```bash
git clone <this repo>

cd kt-sample-app

./gradlew nativeCompile

./app/build/native/nativeCompile/my-app
```




