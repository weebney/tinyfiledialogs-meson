project('tinyfiledialogs', 'c', version: 'v3.18.2', license: 'Zlib')

tinyfiledialogs_sources = [
  'tinyfiledialogs/tinyfiledialogs.h',
  'tinyfiledialogs/tinyfiledialogs.c',
]

tinyfiledialogs_inc = include_directories('tinyfiledialogs/')
tinyfiledialogs_lib = static_library(
  'tinyfiledialogs',
  tinyfiledialogs_sources,
  include_directories: tinyfiledialogs_inc,
)

tinyfiledialogs_dep = declare_dependency(include_directories: tinyfiledialogs_inc, link_with: tinyfiledialogs_lib)
