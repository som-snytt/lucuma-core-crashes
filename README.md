# lucuma-core-crashes

These are crashes generated on clean builds of lucuma-core, with

```
openjdk version "11.0.11" 2021-04-20
OpenJDK Runtime Environment GraalVM CE 21.1.0 (build 11.0.11+8-jvmci-21.1-b05)
OpenJDK 64-Bit Server VM GraalVM CE 21.1.0 (build 11.0.11+8-jvmci-21.1-b05, mixed mode, sharing)
```

via

```bash
while (printf "\033c"; git clean -xdf; sbt compile); do :; done
```

