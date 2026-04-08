# CubeMart Ad Service

![CubeMart](https://img.shields.io/badge/CubeMart-Ads-0f766e)
![Java](https://img.shields.io/badge/Java-Service-007396)
![gRPC](https://img.shields.io/badge/gRPC-Advertising-1f2937)

The Ad service returns contextual product advertisements for CubeMart based on page and product context.

## Building locally

The Ad service uses gradlew to compile/install/distribute. Gradle wrapper is already part of the source code. To build Ad Service, run:

```
./gradlew installDist
```
It will create an executable script at `build/install/hipstershop/bin/AdService`.

### Upgrading gradle version
If you need to upgrade the version of gradle then run

```
./gradlew wrapper --gradle-version <new-version>
```

## Building docker image

From the repo root, run:

```
docker build ./
```
