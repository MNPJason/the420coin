Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the the420coind tests manually, launch `src/test/test_the420coin`.

To add more the420coind tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the the420coin-qt tests manually, launch `src/qt/test/test_the420coin-qt`

To add more the420coin-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
