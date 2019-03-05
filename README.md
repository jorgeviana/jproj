# jproj
Simple Java 8 with Maven project generator

### Install
```
export PATH=$PATH:"$PATH_TO_JPROJ"/src
```

### Usage

```
jproj "$ARTIFACT_ID" "$GROUP_ID"
```

Omitting GROUP_ID will result in default value: **io.github.jorgeviana**
```
jproj "$ARTIFACT_NAME"
```


### Run Tests
```
brew install shellcheck
brew install bats-core
```
```
./build
```

### Watch mode
> Don't forget to install shellcheck and bats-core

```
./watch
```
