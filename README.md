# Testing Gradle MultiModule Build

Trying to follow this project structure: https://docs.gradle.org/current/userguide/declaring_dependencies_between_subprojects.html#sec:project_jar_dependencies

But when I run `gradle build`, I'm getting:
```
FAILURE: Build failed with an exception.

* Where:
Build file 'D:\test-modules\api\build.gradle' line: 2

* What went wrong:
Plugin [id: 'myproject.java-conventions'] was not found in any of the following sources:

- Gradle Core Plugins (plugin is not in 'org.gradle' namespace)
- Plugin Repositories (plugin dependency must include a version number for this source)

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 913ms
```