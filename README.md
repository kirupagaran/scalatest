AUTHOR: KIRUPA DEVARAJAN
Programming Language: SCALA

ENVIRONMENT
###########
Scala code runner version 2.11.7
SBT

DIRECTORY STRUCTURE
###################

suncorp
├── build.sbt
├── project
│   ├── build.properties
│   └── plugins.sbt
├── README.md
└── src
    ├── main
    │   └── scala
    │       └── DeveloperTests
    │           └── Implementation
    │               ├── SmartSeq.scala
    │               ├── SmartString.scala
    │               
    └── test
        ├── resources
        │   └── scala_book.txt
        └── scala
            └── DeveloperTests
                ├── StringTests.scala
                └── Utils
                    └── FileUtils.scala

11 directories, 9 files

EXECUTION INSTRUCTIONS
######################

1) Ensure scala and sbt is installed on the Linux machine
2) Unzip the code file. Open the terminal(Linux) and cd into the folder 'suncorp'
3) Type 'sbt test' having 'suncorp' as the root folder to run the tests.
