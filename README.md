pdfa-testsuite
==============

Test suite for ISO-19005 (PDF/A) conformance
--------------------------------------------

Included are a collection of PDF documents that should either pass or fail
a conformance test against the specified ISO-19005 profile.
The description.txt file lists the reason they should pass or fail.

This collection was inspired by the [Isartor test suite](http://www.pdfa.org/2011/08/isartor-test-suite/)
and follows a similar layout with respect to test case names, including the
section of the PDF/A specification to which each test refers. Unlike Isartor
we have also added _valid_ documents which test a particular area of the specification.

Please contact [BFO Support](mailto:support@bfo.com) if you wish to
collaborate on this project and add new test cases. We intend this collection
to be continually updated with new tests, ideally from as many vendors as possible,
and perhaps to grow to cover PDF/X, PDF/UA and other variations as well. We also welcome
emails about this suite, but suggest if you're on the [PDF Association](http://www.pdfa.org)
mailing list you direct them there.


The naming convention for each test is:
````
pdfa2-6-1-3-bfo-t01-fail.pdf
|       |    |   |    |
|       |    |   |    +-- Whether the test is expected to pass or fail
|       |    |   |
|       |    |   +-- Test number
|       |    |
|       |    +-- Original creator of the test, i.e. who to email if it's wrong!
|       |
|       +-- Section of the specification being tested
|
+-- ISO-19005 revision that's being targetted - pdfa1, pdfa2, pdfa3
````


The files here are licensed under the [Creative Commons Public License](http://creativecommons.org/licenses/by/3.0/legalcode).

