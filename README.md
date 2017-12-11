# Secure Systems Lab: Sample Documents

Welcome to the Sample Documents repo for the [Secure Systems Lab
(SSL)](https://ssl.engineering.nyu.edu/)! Below you can find samples of text,
documents, GitHub templates, and configuration files typically available on SSL
project repos.

These samples should be reviewed and edited to suit a project's needs.  We encourage
you to explore [The Update Framework](https://github.com/theupdateframework/tuf)
repo to learn how these documents can be used in practice.  Many of the sample
documents can satisfy some of the requirements for the [Core Infrastructure Initiative
(CII) Best Practices Badge](https://bestpractices.coreinfrastructure.org/).


* Acknowledgements -- A project's README should
[acknowledge](ACKNOWLEDGEMENTS.md) who manages the project and indicate any
grants that might support the project.

* Project governance -- Our projects should be transparent about
[governance](GOVERNANCE.md) procedures and the handling of contributions.  What
is the role of a project maintainer?  How are maintainers added and removed?

* Vulnerability reports -- Contributors and users of a project should be given
instructions on how to submit [vulnerability reports](vulnerability-reports.md)
and bugs.

* Maintainers -- A project should indicate the people who
[maintain](MAINTAINERS.txt) it and any relevant information about the
maintainer(s), such as their email address, PGP keys, etc.

* GitHub issue template -- Feature requests or bug reports should contain
sufficient information that others can use to implement the feature or
reproduce the bug.  An [issue template](.github/ISSUE-TEMPLATE.md) can be added
to a GitHub repository that is presented to users when they attempt to create a
new issue.

* GitHub pull request template -- Like the GitHub issue template, users
can be given a [skeleton of the pull request
summary](.github/PULL-REQUEST-TEMPLATE.md) when they try to submit a pull
request.  GitHub templates should encourage users to provide enough information
that is helpful to others.

* Roadmap -- A project roadmap can help users of the project.  It is also a
practice recommended by the CII Best Practices program.

* Pylint configuration -- A static analysis tool can detect common and subtle
programming errors, confirm that code conforms to the project's coding
standard, and warn you about potential issues.
[Pylint](https://www.pylint.org/) provides static code analysis for Python code.
[pylintrc](pylintrc) is an example configuration file for one of our projects,
which can verify that Python code uses two spaces for indentation, variables
are correctly named, etc.

* Tox configuration -- A [configuration file](tox.ini) for
[Tox](https://tox.readthedocs.io/en/latest/) is provided, which can automate
testing in a virtual environment.

* Travis configuration -- [Continuous
integration](https://en.wikipedia.org/wiki/Continuous_integration) is "the
practice of merging all developer working copies to a shared mainline several
times a day."  [Travis CI](https://docs.travis-ci.com/user/languages/python/)
is a popular continuous integration system with the open-source community.
[.travis.yml](.travis.yml) is an example configuration file.

* Dependency management -- Our projects should always require the latest
versions of dependencies.  The [pyup.io](https://pyup.io) app is a handy tool
for Python projects that can notify repo admins when a new version of a
dependency is available.  It can even submit pull requests that updates a
project's requirement files.  [.pyup.yml](.pyup.yml) is an example
configuration file.

----

For more information, please visit the
[Secure Systems Lab web page](https://ssl.engineering.nyu.edu/) at
[NYU Tandon School of Engineering](https://engineering.nyu.edu/).
