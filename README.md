# requestpathmatchinghelper-test

1.6

```
docker run -it --rm -v $HOME/.m2:/root/.m2 -v $(pwd):/workspace \
       maven:3-jdk-6 mvn -f /workspace/pom.xml test \
       -Dmaven.compiler.source=1.6 -Dmaven.compiler.target=1.6
```

1.7

```
docker run -it --rm -v $HOME/.m2:/root/.m2 -v $(pwd):/workspace \
       maven:3-jdk-7 mvn -f /workspace/pom.xml test \
       -Dmaven.compiler.source=1.7 -Dmaven.compiler.target=1.7
```

1.8

```
docker run -it --rm -v $HOME/.m2:/root/.m2 -v $(pwd):/workspace \
       maven:3-jdk-8 mvn -f /workspace/pom.xml test \
       -Dmaven.compiler.source=1.8 -Dmaven.compiler.target=1.8
```

11

```
docker run -it --rm -v $HOME/.m2:/root/.m2 -v $(pwd):/workspace \
       maven:3-jdk-11 mvn -f /workspace/pom.xml test \
       -Dmaven.compiler.source=11 -Dmaven.compiler.target=11
```

