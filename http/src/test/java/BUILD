junit_tests(
  name='java',
  dependencies=[
    '3rdparty/jvm/junit',
    'finatra/http:test-deps',
    'finatra/httpclient',
    'finatra/inject/inject-server:test-deps'
  ],
  fatal_warnings=False,
  sources=rglobs('com/twitter/finatra/integration/*.java'),
  resources=[
    'finatra/http/src/test/resources'
  ]
)

java_library(name='test-deps',
  dependencies=[
    '3rdparty/jvm/com/google/inject:guice'
  ],
  fatal_warnings=False,
  sources=globs('com/twitter/finatra/test/*.java')
)
