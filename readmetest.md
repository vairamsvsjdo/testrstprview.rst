.. default-role:: code

=====================================
  Naming Conventions.
=====================================

testing docs.
__ http://www.jaydevops.com

.. contents:: Table of contents:
   :local:
   :depth: 5

Introduction
============

1.0 Introduction
----------------
This document provides naming conventions followed. 
This document depends on the following documents:

  - `Robot Framework User Guide`__ user guide.
  - `How To Write Good Test Cases`__ do's and don'ts in github.
  - `Robot Framework API documents`__ read the docs.

__ http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html
__ https://github.com/robotframework/HowToWriteGoodTestCases/blob/master/HowToWriteGoodTestCases.rst
__ https://robot-framework.readthedocs.io/en/3.0.2/index.html


2.0 References
------------------

http://www.sphinx-doc.org/en/stable/config.html

http://www.sphinx-doc.org/en/stable/tutorial.html

Theming: http://www.sphinx-doc.org/en/stable/theming.html

Templating: http://www.sphinx-doc.org/en/stable/templating.html

reStructured Text Primer: http://www.sphinx-doc.org/en/stable/rest.html

Different programming code block (robotframework, python, bat): http://build-me-the-docs-please.readthedocs.io/en/latest/Using_Sphinx/ShowingCodeExamplesInSphinx.html

3.0 Naming Conventions
----------------------

The purpose of this document is to provide naming conventions for files, variables, test cases, keywords, variable files.

3.1 File Names
--------------

1. kw.rst - a file containing only keywords
2. tc.rst - a file containing only test cases
3. fe.rst - a file containing keyword that is called by a test case that defines a feature. A feature is a gherkin style scenario construct.
4. variable files are python files with get_variables method defined as the return method.


To make test scripts to behave efficiently, use cases are broken down into smaller use case document with naming convention uc234-01a.

* uc234  identifies use case 234
* 01a identifies  a flow within use case 234.


3.2 Variable Names returned as a List
-------------------------------------

get_variables method returns a list of variables to use within robot scripts. Use Upper Case to denote that it is a global variable include even though it is case insensitive to robot framework.

3.3 Package, Class, Method Names

Use Python naming conventions defined in PEP8


