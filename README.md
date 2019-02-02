# dag-lib-java
Java library for protocol clients

## Introduction
This repo contains Java source code for the [`Spendr`](https://github.com/trust-net/dag-lib-go/blob/master/docs/SpendrApp.md#spendr-a-value-transfer-application) test application from the [`dag-lib-go`](https://github.com/trust-net/dag-lib-go) repo.

## Dependencies
This code requires following dependencies:

```
implementation 'com.madgag.spongycastle:core:1.54.0.0'
implementation 'com.madgag.spongycastle:prov:1.54.0.0'
implementation 'com.madgag.spongycastle:pkix:1.54.0.0'
implementation 'com.madgag.spongycastle:pg:1.54.0.0'
implementation group: 'com.fasterxml.jackson.core', name: 'jackson-core', version: '2.9.8'
implementation group: 'com.fasterxml.jackson.core', name: 'jackson-databind', version: '2.9.8'
implementation group: 'com.fasterxml.jackson.core', name: 'jackson-annotations', version: '2.9.8'
implementation 'org.springframework.android:spring-android-rest-template:2.0.0.M3'
implementation group: 'org.slf4j', name: 'slf4j-android', version: '1.7.25'
```

## How to use it
Either copy the files directly into your project, or build a jar file and drop into library.
> An example of this code in use is the [Spendr Android Client](https://github.com/trust-net/SpendrClient)
