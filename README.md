# Basic Statistics

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> 39baf12 (cleared up running instructions)
Basic Statistics is a Java-based implementation for computing statistics on a set of numbers.
This implementation is intended to be used in software engineering courses as
a subject software system.

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
Basic Statistics uses the Apache Ant build system. **Make sure that you have [Ant](https://ant.apache.org) installed.**

#### How to build Basic Statistics and run its tests from the terminal:

1. Change into the Basic Statistics root directory, which contains the *build.xml* build file.

2. Run `ant compile` to compile Basic Statistics. The compiled class files will be in the *bin* directory.

4. Run `ant test` to run all Basic Statistics unit tests.

5. Run `ant clean` whenever you want to clean up the project (i.e., delete all generated files).

#### How to run Basic Statistics from the terminal:

1. After building the project (i.e., running `ant compile`), run: `java -cp bin BasicStats`. The application's GUI will show up.

#### Program features:
* Displays a set of entered numbers.
* Computes the mean of the set of numbers.
* Computes the median of the set of numbers.
* Computes the mode of the set of numbers.

## Troubleshooting

#### Outdated version of JUnit
If your system uses an outdated version of JUnit, you may encounter the following error:
```
[junit] junit/framework/JUnit4TestAdapterCache
[junit] java.lang.NoClassDefFoundError: junit/framework/JUnit4TestAdapterCache
```
Run `ant -lib lib/ <target>` to explicitly use JUnit4, which is provided in the *lib* directory. For example, run `ant -lib lib/ test` to run all Basic Statistics unit tests.

#### Java JDK not installed or misconfigured
If a Java JDK is not installed or properly configured on your system, you may encounter the following error: 
```
BUILD FAILED
build.xml:17 Unable to find a javac compiler;
```
Make sure that you have a JDK installed and that the JAVA_HOME environment variable is properly set.
=======
How to build:
=======
How to build (from Terminal):
>>>>>>> e4e4cff (Updated README)
=======
A Java-based implementation for descriptive statistics. This
implementation is merely intended to be used in software engineering courses.
=======
A Java-based implementation for computing statistics on a set of numbers.
This implementation is intended to be used in software engineering courses as
a subject software system.
>>>>>>> a13d6cf (improved description)

How to build and test (from Terminal):
>>>>>>> 7b43acb (Updated README file.)
=======
How to build and run tests from the terminal:
>>>>>>> d379757 (added more info about Ant)
=======
Basic Statistics uses the Apache Ant build system. **Make sure that you have [Ant](https://ant.apache.org) installed.**
>>>>>>> 39baf12 (cleared up running instructions)

#### How to build Basic Statistics and run its tests from the terminal:

1. Change into the Basic Statistics root directory, which contains the *build.xml* build file.

2. Run `ant compile` to compile Basic Statistics. The compiled class files will be in the *bin* directory.

4. Run `ant test` to run all Basic Statistics unit tests.

5. Run `ant clean` whenever you want to clean up the project (i.e., delete all generated files).

#### How to run Basic Statistics from the terminal:

1. After building the project (i.e., running `ant compile`), run: `java -cp bin BasicStats`. The application's GUI will show up.

#### Program features:
* Displays a set of entered numbers.
* Computes the mean of the set of numbers.
* Computes the median of the set of numbers.
* Computes the mode of the set of numbers.

<<<<<<< HEAD
<<<<<<< HEAD
2. In the root directory, run `ant test` to run tests.


Features:
* Displayed Numbers
* Mean
* Median
* Mode
>>>>>>> 5b5e6b8 (Updated the README)
=======
Program features:
* Displayed numbers
* Mean computation
* Median computation
* Mode computation
>>>>>>> 7b43acb (Updated README file.)
=======
## Troubleshooting

#### Outdated version of JUnit
If your system uses an outdated version of JUnit, you may encounter the following error:
```
[junit] junit/framework/JUnit4TestAdapterCache
[junit] java.lang.NoClassDefFoundError: junit/framework/JUnit4TestAdapterCache
```
Run `ant -lib lib/ <target>` to explicitly use JUnit4, which is provided in the *lib* directory. For example, run `ant -lib lib/ test` to run all Basic Statistics unit tests.

#### Java JDK not installed or misconfigured
If a Java JDK is not installed or properly configured on your system, you may encounter the following error: 
```
BUILD FAILED
build.xml:17 Unable to find a javac compiler;
```
Make sure that you have a JDK installed and that the JAVA_HOME environment variable is properly set.
>>>>>>> 39baf12 (cleared up running instructions)
