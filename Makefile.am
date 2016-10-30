
AUTOMAKE_OPTIONS=dejagnu

bin_PROGRAMS = travis-docker-test

travis_docker_test_SOURCES = src/main.c
travis_docker_test_LDFLAGS = -static

RUNTESTDEFAULTFLAGS = \
	--tool travis-docker-test \
	TOOL_PATH=`pwd`/travis-docker-test \
	--srcdir $$srcdir/testsuite
