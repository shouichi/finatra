java_library(name='java',
  provides = artifact(
    org = 'com.twitter.inject',
    name = 'inject-thrift-client-java',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/com/google/inject:guice',
  ],
  fatal_warnings=False,
  sources=rglobs('*.java'),
)
