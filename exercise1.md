## Discussion about exercise 1, the text or requirements presented here is not directly related to the project found in this repo or elsewhere.

The team is working with an application using Python programming language. When evaluating the different steps and tools needed for implementing a CI pipeline as a part of the project, particularly concerning the linting, testing and building steps, the following decisions has been made:

- For linting the code, the team uses Pylint which is a static code analysis tool for Python.
- Testing is performed at unit, integration and end-to-end levels. For unit testing, the team uses the Python build-in testing framework unittest. For integration testing, the team uses Pytest framework. For the end-to-end testing, Robot Framework is used with the SeleniumLibrary to perform testing on the web-based graphical user interface.
- No specific building tooling is needed for the project, since all the source code can be directly executed with the Python interpreter.

The team is using Microsoft Azure services for storing the code in repositories and as the CI tool Azure Pipelines is used. Azure Pipelines features rich continuous integration and delivery options, which makes it effortless to merge code and publish new versions of the application in a robust manner. The Azure Pipelines is used as cloud-based service, which makes it a secure and effortless solution to set up and maintain.
