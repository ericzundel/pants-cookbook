# src/java/hello/BUILD
jvm_binary(name = 'hello',
  main = 'hello.HelloWorld',
  dependencies = [
    ':lib',
  ],
)

java_library(name = 'lib',
    sources = [ 'HelloWorld.java' ],
)
