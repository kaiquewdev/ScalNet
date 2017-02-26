:)
# ScalNet

ScalNet is a wrapper around deeplearning4j emulating a [keras](https://github.com/fchollet/keras) like api for deep learning.

ScalNet is STILL ALPHA and we are open sourcing this in an attempt to get feedback.

You will have to build from source to use ScalNet (this includes the dl4j toolchain)

Come in to [gitter](https://gitter.im/deeplearning4j/deeplearning4j) if you are interested in learning more.

# How to build

Currently ScalNet depends on deeplearning4j and nd4j SNAPSHOTs. Please install these package in your local machine first with `mvn install`.

- [deeplearning4j/deeplearning4j](https://github.com/deeplearning4j/deeplearning4j)
- [deeplearning4j/nd4j](https://github.com/deeplearning4j/nd4j)

Target for scala-2.11

```scala
$ mvn package -Pscala-2.11.x
```

Target for scala-2.10

```scala
$ mvn clean -Pscala-2.10.x
```