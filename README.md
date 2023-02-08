
#  DSV (Delimiter-separated values) files into JSONL (JSON line) format.
- 

A brief description of what this project does and who it's for
- Requirements:
    + Dates in JSONL output file must be in YYYY-MM-dd format.
    + The project can be built using Maven in a terminal, e.g. with "mvn package".    
    + Any DSV file with any arbitrary data should be convertible with this tool. This means the test files are only examples, the real structure of the data at runtime should be dynamic.
    + An executable JAR is created to allow user to run the conversion in a terminal.
    + The user can specify the input file and any additional parameters if necessary via command-line arguments.
    + Both reading input and writing output files should be done in a streaming manner:
        * You must never store all data entries in memory at the same time (Expect millions of entries in a real use case).
        * You should use Java Stream API for stream processing.
    + Unit tests with either JUnit 4 or 5 should be created for the project. Both of the provided test input files should be used in the tests.

## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Demo

Insert gif or link to demo

Replacing D:\java\Java task\dsv-converter\target\dsv-converter-1.0-SNAPSHOT.jar with D:\java\Java task\dsv-converter\target\dsv-converter-1.0-SNAPSHOT-shaded.jar
[[1;34mINFO[m] Dependency-reduced POM written at: D:\java\Java task\dsv-converter\dependency-reduced-pom.xml
[[1;34mINFO[m] 
[[1;34mINFO[m] [1m--- [0;32mmaven-install-plugin:2.4:install[m [1m(default-install)[m @ [36mdsv-converter[0;1m ---[m
[[1;34mINFO[m] Installing D:\java\Java task\dsv-converter\target\dsv-converter-1.0-SNAPSHOT.jar to C:\Users\Vivek Mishra\.m2\repository\org\example\dsv-converter\1.0-SNAPSHOT\dsv-converter-1.0-SNAPSHOT.jar
[[1;34mINFO[m] Installing D:\java\Java task\dsv-converter\dependency-reduced-pom.xml to C:\Users\Vivek Mishra\.m2\repository\org\example\dsv-converter\1.0-SNAPSHOT\dsv-converter-1.0-SNAPSHOT.pom
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m
[[1;34mINFO[m] [1;32mBUILD SUCCESS[m
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m
[[1;34mINFO[m] Total time:  01:20 min
[[1;34mINFO[m] Finished at: 2023-02-08T14:24:48+05:30
[[1;34mINFO[m] [1m------------------------------------------------------------------------[m

## 🚀 About Me
I'm a Java Backend Developer

