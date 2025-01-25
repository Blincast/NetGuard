Install ninja
```
sudo apt install ninja-build -y
```

Create a `keystore.properties` file with following content
```
storeFile=key-path
storePassword=store-pwd
keyAlias=alias
keyPassword=key-pwd
```

Then, if on a terminal
```
./gradlew assembleRelease --warning-mode=all
```
