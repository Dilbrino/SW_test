# SW_test
# Oblig_3_ver_1
* This is a documentation of how I performed in this oblig_3.
* Got help and explations from student assistant 
* To carry out this oblig_3, I went to github's official home page and used their dox.
* It explained what we were going to do step by step.
* First we used git bash to check if we had the updated version of github 
* Then we used gitbash to connect the project to github. 
* After we connect the project to github. 
* The last thing we did was create a new flow for testing and this function.
* edit steps workflow:

uses: actions/checkout@v2
name: Set up JDK  uses: actions/setup-java@v1 with: java-version:
name: Build with Maven run: mvn -B package –file pom.xml
name: Test with Maven run: mvn -B test –file pom.xml
This is everything that i needed for a basic .yml script to run my tests. I tested this a few times and it was OK
* And done.
