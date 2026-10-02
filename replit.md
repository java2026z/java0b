# Imported Java/Maven project

## Run on Replit

This project is a Java console application. Its entry point is
`src/main/java/Main.java`, which prints a greeting and then exits.

- Run the configured `Start application` workflow to execute it.
- Expected console output: `Hello world JPWP2!`. The workflow then finishes normally; this is not a web server.
- Build and test manually with `mvn test`.
- Run the entry point directly with `javac -d . src/main/java/Main.java && java -cp . Main`.

The Java toolchain is provided by the Replit project configuration.
