project('mINI', 'cpp', version: '0.9.15', license: 'MIT')

# For tests
add_global_arguments('-I../src', language: 'cpp')

mINI_dep = declare_dependency(include_directories: include_directories('src'))

subdir('src')
subdir('tests')