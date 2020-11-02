# Ninth Grader Class

For the warm-up, you'll practice working with inheritance and create the NinthGrader class. The NinthGrader class should be a subclass of the Student Class.

Your NinthGrader class should contain the following components:
* This class will not contain any additional instance variables (it will inherit firstName, lastName, and classYear) 
* Two constructors to create a Student: one default/no-argument constructor and one with **two** parameters (all NinthGraders are class of 2024, so a classYear parameter is unnecessary)
* doSomething() method that just printed out something that the NinthGrader is doing (e.g. "I am preparing for a Harkness discussion!")
* toString() method that returns the Ninth Grader’s full name and class year, as well as a note denoting that they are a Ninth Grader; toString() should return something like "Joe Smith, 2024 (Ninth Grader)"
* This class will not contain any additional getters and setters, but note that it will inherit getters/setters for all three variables

Add code to [NinthGrader.java](src/main/java/NinthGrader.java) to define the class, and then add code to [NinthGraderClient.java](src/main/java/NinthGraderClient.java) to test your code

## Run your client code with:
```shell script
make run
```