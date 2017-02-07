cxx_library(
  name = 'awesome',
  header_namespace = 'awesome',
  exported_headers = subdir_glob([
    ('awesome-lib/export', '**/*.hpp'),
  ]),
  headers = subdir_glob([
    ('awesome-lib/include', '**/*.hpp'),
  ]),
  srcs = glob([
    'awesome-lib/src/**/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
)
