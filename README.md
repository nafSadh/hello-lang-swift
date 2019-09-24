# Swift
Simple hello world program in swift

# dependencies
clang, libicu-dev, & git (Linux/Unix)

# building

### build and run in macos
```console 
swift hello_world.swift 
```

### build and run in Linux environment

#### Install Dependencies
``` console
sudo apt-get install clang libicu-dev -y
wget https://swift.org/builds/swift-4.1.2-release/ubuntu1404/swift-4.1.2-RELEASE/swift-4.1.2-RELEASE-ubuntu14.04.tar.gz
tar -xvzf swift-4.1.2-RELEASE-ubuntu14.04.tar.gz -C ~/swift
```

#### Configuring environment variables

``` console
sudo vi ~/.bashrc export PATH=~/swift/swift-4.1.2-RELEASE-ubuntu14.04/usr/bin:$PATH
```


#### Building & Running
``` console 
swift build
.build/debug/helloworld-project
 ```




