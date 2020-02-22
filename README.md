# android building env contained

- A docker image of android build environment based on ubuntu:bionic;
- NDK bundled;
- git installed;

## use

```bash
docker pull shinchven/android-build:29
```

## build android app from command line

[official guide: Build your app from the command line](https://developer.android.com/studio/build/building-cmdline)

```bash
chmod +x ./gradlew # grant execution permission
./gradlew task-name # run your gradle task
```

## cache

Cache your gradle and local repos for fast build.

```path
/root/.gradle/wrapper
```

## link

- [Docker Hub](https://hub.docker.com/)
- [GitHub](https://github.com/ShinChven/android-build)




