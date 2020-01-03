# android-build

- A docker image of android build environment;
- NDK bundled;

## use

```bash
docker pull shinchven/android-build:29
docker pull shinchven/android-build:28
```

## build android app from command line

[official guide: Build your app from the command line](https://developer.android.com/studio/build/building-cmdline)

```bash
chmod +x ./gradlew # grand execution permission
./gradlew task-name # run your gradle task
```

## cache

Cache your gradle and local repos.

```path
/root/.gradle/
```




