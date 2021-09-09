**Overview**
Checkstyle is a development tool to help programmers write Java code that adheres to a coding standard. It automates the process of checking Java code to spare humans of this boring (but important) task. This makes it ideal for projects that want to enforce a coding standard.

Checkstyle is highly configurable and can be made to support almost any coding standard. An example configuration files are supplied supporting the Sun Code Conventions, Google Java Style.

A good example of a report that can be produced using Checkstyle and Maven can be seen here .

**Features**
Checkstyle can check many aspects of your source code. It can find class design problems, method design problems. It also has the ability to check code layout and formatting issues.

For a detailed list of available checks please refer to the Checks page.

**Download**
The latest release of Checkstyle can be downloaded from the GitHub releases page, or Maven central.

If you want to live on the bleeding edge, you can checkout the current development code from GitHub and compile yourself. Or use jitpack.io to build and get artifacts you need (you can even build your forked repo).

Previous Version Documentation
Current site contains documentation only for latest, released version. We only support this latest version. We highly recommend read latest documentation first.
However, you might need documentation for previous releases because you are still using an older version and latest version describe some features that does not work for you.
You can find documentation for most old versions using a URL format like https://checkstyle.sourceforge.io/version/X.X where "X.X" is the version number.
Example: https://checkstyle.sourceforge.io/version/6.18 for version 6.18.

**Backport**
Since Checkstyle 7, some users have been unable to continue upgrading to newer versions of the utility because of the new JDK 1.8 compile requirement. The development team doesn't have the resources to keep updating the utility for older JDKs for those that can't work with the latest version.

However, some members of the community have created an unofficial backport of the latest Checkstyle releases to be run with JDKs as old as 1.6. If you wish to continue using new Checkstyle versions on older JDKs, we recommend you either checkout the github site or the documentation site on how to use the backport version of the utility, in place of the official Checkstyle version.

**Development Cycle**
Releases will happen at the end of each month if functional changes exist in the master branch of our repo. For the exact day, please follow our milestones.

Checkstyle is not using Semantic Versioning (reasons in issue #3709)

**Limitations**
Checkstyle is a single file static analysis tool, for more details please read the full list of limitations.