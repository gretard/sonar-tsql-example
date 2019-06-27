# TSQL project example #
This folder contains example TSQL project and illustrating usage of sonar-scanner with open source sonar -sql-plugin and Red Gate's SQLCodeGuard.

# Usage #
Execute the following:
 1. Setup SonarQube and [open source sonar-sql-plugin](https://github.com/gretard/sonar-sql-plugin)
 2. Update *sonar-project.properties* file with path to SQLCodeGuard executable
 3. Run sonar-scanner

TSQL sample project should now be visible in SonarQube server with coverage results.
