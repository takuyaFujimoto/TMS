# TMS

## Environment construction procedure manual (OS / MAC)

### 1 Homebrew
- [Script execution at link destination](https://brew.sh/index_ja)

### 2 java8
- `brew cask install caskroom/versions/zulu8`
- `java -version`
- Plase set environment variable
    - `export PATH=$PATH:/Library/Java/JavaVirtualMachines/zulu-8.jdk/Contents/Home/bin`
    - `JAVA_HOME=/Library/Java/JavaVirtualMachines/zulu-8.jdk/Contents/Home`

### 3 gradle version 5.x.x
- `brew install gradle`
- `brew -v`

### 4 Visual Studio Code
- [DownLoad](https://code.visualstudio.com/download)
    - Get plugin "Java Extension Pack"
    - Plase set Visual Studio Code settings.json
        - `"java.home": "/Library/Java/JavaVirtualMachines/zulu-8.jdk/Contents/Home"`


※更新中

