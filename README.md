# How to run
* mvn clean install
* go mod init <name_module> (my module: github.com/hovanduanit/lms-proto)
* docker run --volume "$(pwd):/workspace" --workdir /workspace bufbuild/buf build
* docker run --volume "$(pwd):/workspace" --workdir /workspace bufbuild/buf generate
* go mod tidy
