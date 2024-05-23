CNF Testing Cookbook
====================
The purpose of this chapter is to direct the reader to information regarding
the test suites available and where to find the test suite code for workloads.

The description of the tests can be found in the
CNTI CNF Testsuite Descriptions :cite:p:`rc2-cnti-testsuite-list-of-tests`.

The installation of the CNCF test suite is described in the CNTI CNF Testsuite
Installation :cite:p:`rc2-cnti-testsuite-install`.

Some of the necessary tests are found in Kubernetes documentation
:cite:p:`rc2-k8s-recommended-labels`.

Functest
========
RC2 platform testing is executed via Functest. Funbctest can be configured to
execute the CNCF Testsuite as part of Functest. At this time, the ability to
select specifc CNCF CNF tests is  not available. Thus all of the CNCF Test
will execute when called by Functest. the results of tests that are not
**Must** or **Must Not** should be ignored.
