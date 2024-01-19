# KoelApp
### Selenium WebDriver, test automation framework
The framework is built according to the Page Object Model (POM) design pattern. The POM is a concept that is used a lot to automate multiple page applications. Here we segregate the automation from our tests. This makes the framework more maintainable.

## Getting started

To run the basic scene:

1. Clone / download this repository
2. You must have Java installed. Download it from Oracle http://www.oracle.com/technetwork/java/javase/downloads/index.html and install it.
3. Install IntelliJ IDEA.
Download it from Jet BRAINS https://www.jetbrains.com/idea/download/ and install it.
4. Install Maven. Maven can be downloaded from http://maven.apache.org/download.cgi.
5. Set up the environment variables – M2_HOME and Path in .bash_profile folder.
If .bash profile not exist create with following command:
 * $touch .bash_profile
 * Next open .bash_profile with command $open -e .bash_profile
 * Next $export M2_HOME=/Applications/apache-maven-3.8.4
 * And $export PATH=$PATH:M2_HOME/bin
 * Save and close
 6. Run all tests.
    To run all the unit tests with Maven run command $ mvn clean test. If you use clean, all the resources and compiled Java code generated by maven in target directory will be cleaned, and run tests freshly.



## References

* Selenium - [http://www.seleniumhq.org/](http://www.seleniumhq.org/)
* Maven - [http://maven.apache.org/](http://maven.apache.org/)
