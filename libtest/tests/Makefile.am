libtest_tests_TESTS			= \
	libtest/tests/test_mock_transport

EXTRA_DIST += libtest/tests/CMakeLists.txt

check_PROGRAMS					+= ${libtest_tests_TESTS}

libtest_tests_test_mock_transport_CFLAGS	= $(TEST_CFLAGS)
libtest_tests_test_mock_transport_LDADD	= \
	$(TEST_LDADD)
