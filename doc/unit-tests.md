Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the alphacupd tests manually, launch src/test/test_alphacup .

To add more alphacupd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the alphacup-qt tests manually, launch src/qt/test/alphacup-qt_test

To add more alphacup-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
