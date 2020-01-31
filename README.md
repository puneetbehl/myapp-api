# Sample Micronaut API project

This is a sample Micronaut project to share HTTP client code among a few Micronaut applications as library.

Follow the steps to customize as per your need: 
1. Change the default group in `build.gradle` as per your needs.
2. Update checkstyle rules under `/checkstyle/oracle.xml`.
3. Under `/gradle/publishing.gradle` file change the artifact id to projectName-api and change the Maven URL to your nexus.
4. Rename the package `myapp.api`.