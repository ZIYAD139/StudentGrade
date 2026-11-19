# Running the tests

The test suite uses JUnit 4.13.2. This NetBeans Ant project expects these
dependencies in the `lib` directory at the project root:

- `junit-4.13.2.jar` from
  https://repo.maven.apache.org/maven2/junit/junit/4.13.2/junit-4.13.2.jar
- `hamcrest-core-1.3.jar` from
  https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar

Create `lib` if needed and place both JAR files there. The project classpath
references these paths relatively, so it works across machines. With Apache
Ant installed, run `ant test` from the project root.
