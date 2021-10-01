## HACCLE

## Prerequisites
  [JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
  
  [sbt](https://www.scala-sbt.org/1.0/docs/)
  
  c++ compiler
  
    
## Build 
  
  1. clone this project
  2. pull the submodule: git submodule update --init --recursive
  3. compile: 
     * Go the root of directoy where the project is cloned 
     * command: sbt
     * command: compile
  4. run a single test: 
     * command: testOnly path -- -t testname 
     * example: testOnly lms.security.test.ResMergeSort -- -t "r-merge-sort"
     
  5. run all tests under a directory: 
     * command: testOnly path
     * example: testOnly lms.security.test.ResMergeSort