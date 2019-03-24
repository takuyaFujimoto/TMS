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
- `gradle -v`

### 4 Visual Studio Code
- [DownLoad](https://code.visualstudio.com/download)
    - Get plugin "Java Extension Pack"
    - Plase set Visual Studio Code settings.json
        - `"java.home": "/Library/Java/JavaVirtualMachines/zulu-8.jdk/Contents/Home"`


### 5 Docker
- [DownLoad](https://docs.docker.com/docker-for-mac/install/)
- Plase kitematic download link below
    - [DownLoad](https://github.com/docker/kitematic/releases)
- Or choise (menu -> kitematic)
    <img width="1627" alt="スクリーンショット 2019-03-25 0 59 04" src="https://user-images.githubusercontent.com/42311219/54882121-24275b80-4e9a-11e9-9175-7ab9edf5dd30.png">

- Please create a Docker hub account
    - [Docker hub](https://hub.docker.com/)
