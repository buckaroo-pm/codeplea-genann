cxx_library(
  name = 'genann',
  header_namespace = '',
  srcs = ['genann.c'],
  exported_headers = [
    'genann.h'
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = ['test.c'],
  deps = [':genann']
)
