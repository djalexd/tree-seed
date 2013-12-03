tree-seed
=========

A reusable POM that contains all basic (core) dependencies

But why?
========

* Tired of copy-pasting the master pom for every new project?
* Hate to manually customize the basic survival kit for your brand new Java/Maven setup?
* When you thought everything is perfect, build fails because annotations are not
supported for source/target 1.3?!

Well, seek no more! Like you, I've had enough copy-paste and prefer a <parent> tag
that sets up the basic, *decent* dependencies:
* Google guava
* Joda time
* slf4j api
* slf4j wrappers (jcl, jul)
* junit (scope = test)
* fest-assert (scope = test)
* mockito (scope = test).

That all to it, enjoy. Forks, issues and PRs are welcome.