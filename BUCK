include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'multiprecision', 
  header_only = True,
  header_namespace = 'boost/multiprecision',
  exported_headers = subdir_glob([
    ('include/boost/multiprecision', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
