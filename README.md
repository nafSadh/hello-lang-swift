# Swift
Simple hello world program in swift

## Dependencies
clang, libicu-dev, & git (Linux/Unix)

## Building

### Build and run in MacOS
```sh 
swift hello_world.swift 
```

### Build and run in Linux environments

Install Dependencies
``` sh
sudo apt-get install clang libicu-dev -y
wget https://swift.org/builds/swift-4.1.2-release/ubuntu1404/swift-4.1.2-RELEASE/swift-4.1.2-RELEASE-ubuntu14.04.tar.gz
tar -xvzf swift-4.1.2-RELEASE-ubuntu14.04.tar.gz -C ~/swift
```

Configuring environment variables
``` sh
sudo vi ~/.bashrc export PATH=~/swift/swift-4.1.2-RELEASE-ubuntu14.04/usr/bin:$PATH
```

Build and run
``` sh 
swift build
.build/debug/helloworld-project
 ```




