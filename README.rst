====
ETOS
====


ETOS (Eiffel Test Orchestration System) is a new test orchestration system which takes away control of how to run and what to run from the system itself and places it into the hands of the relevant engineers.

The idea of having a system dictate what and how to run is finished. Let's bring back control to the testers.

With ETOS we define how to run tests using recipes and we define what to run with collections of recipes.

.. list-table :: ETOS Roles
   :widths: 25 25 25
   :header-rows: 1

   * - :ref:`test-engineer`
     - :ref:`test-automation-engineer`
     - :ref:`system-engineer`
   * - Create collections
     - Create recipes
     - Deploy ETOS
   * - Analyze results
     - Create tests
     - Infrastructure
   * - What to run?
     - How to run?
     - Where to run?

This means that only people who knows how and what to run decide these factors. ETOS will only receive the collection of recipes and executing it accordingly.
You can also mix test suites. For instance, let's say you want to run a "go" unittest and a "python" function test in the same suitt, that's easy to do; just add them to your collection.

This is the strength of ETOS. Relying on the humans to decide what to run, how to run and where to run.

ETOS is a collection of multiple services working together. This repository is a facilitator of versioning, helm charts and documentation.
The services are located in these repositories.

- :ref:`etos-client`
- :ref:`etos-api`
- :ref:`etos-suite-starter`
- :ref:`etos-suite-runner`
- :ref:`etos-test-runner`
- :ref:`etos-environment-provider`
- :ref:`etos-library`
- :ref:`etos-test-runner-containers`


Features
========

- Generic test suite execution based solely on JSON.
- Mix and match test suites, regardless of programming language.
- Separation of concerns between testers, test automation engineers and system engineers.
- Eiffel protocol implementation.


Installation
============

TBD (Helm)


Contribute
==========

| Please write issues in the relevant repositories for where you found the issue.
| If you do not know which repository to write the issue for, feel free to write it here and it will be moved.
| Documentation issues are reported here.

- Issue Tracker: https://github.com/eiffel-community/etos/issues
- Source Code: https://github.com/eiffel-community/etos


Support
=======

If you are having issues, please let us know.
There is a mailing list at: etos-maintainers@google.groups.com or just write an Issue.