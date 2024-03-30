lest_dir = include_directories('lest')

test_casesens = executable('testcasesens', 'testcasesens.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testcasesens', test_casesens)

test_copy = executable('testcopy', 'testcopy.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testcopy', test_copy)

test_gen = executable('testgenerate', 'testgenerate.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testgenerate', test_gen)

test_huge = executable('testhuge', 'testhuge.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testhuge', test_huge)

test_read = executable('testread', 'testread.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testread', test_read)

test_utf8 = executable('testutf8', 'testutf8.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('testutf8', test_utf8)

test_write = executable('testwrite', 'testwrite.cpp', include_directories: lest_dir, cpp_args: [ '-I../src' ])
test('test_write', test_write)