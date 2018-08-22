cxx_library(
  name = 'zupply',
  header_namespace = 'zupply',
  srcs = glob([
    'src/zupply.cpp',
  ]),
  exported_headers = subdir_glob([ # public include files
    ('src', 'zupply.hpp'), # those will be exported
  ]),
  visibility = ['PUBLIC']
)

