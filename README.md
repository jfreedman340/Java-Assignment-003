# Java-Assignment-003
### Input, Packages, Imports, and a static Method
## PART 1 - Build an External Package
1. Watch the below linked video, and follow along on how we build a **Java Archive** artifact (**jar**) from a GitHub project.
[Jar file build from GitHub Project](https://pdx.nv.instructuremedia.com/fetch/QkFoYkIxc0hhUVRKb0U0RGFRUmRkUVFDYkNzSG9QNFVZdz09LS1hYTBhODRlOWU5NTdkMzljZDU4ZThiM2Y1N2RmNDZhMmI4NGUxMmM0.mp4)
1. If you didn't already, attempt to build the artifact, **the jar file** yourself!
[MetaData Extractor Code on GitHub](https://github.com/drewnoakes/metadata-extractor)
1. Watch the below linked video, and follow along to import an external **jar** file into your project!
[Import External Jar into your Project](https://pdx.nv.instructuremedia.com/fetch/QkFoYkIxc0hhUVM0b1U0RGFRVGJkUVFDYkNzSEJmOFVZdz09LS0yYWY5NmMwYzM2MDA0ZGY5YTAzNTQ0NjM0ZTNmYWI2NTk4ZGMyYjRk.mp4)
1. If your artifact creation step was successful, see if you can import your build of the metadata jar file into Java-Assignment-003 after you start PART 2 below!

## PART 2 - Implementation
Just like you do every week now!!!
* Fork my repo
* Using IntelliJ clone your fork locally
* Use IntelliJ to activate the Fall-2022 local branch
* Implement the following assignment:

Your assignment is to use Built-In java classes to:

1. Import the following java Built-In classes.
```
java.nio.file.Paths;
java.util.Scanner;
java.nio.file.Path;
```
1. Read a **jpg file path** from the user.
     * HINT 1: Create a **Scanner** object instance and use it to read a string.
     * HINT 2: Use **Paths** class to get a path from your input!
1. From your path object call a **method** that converts the file path to a **File** type object (**Cause that's what getHiddenSecret declares as its parameters**).
1. Pass the file object as an argument to the pre-written **getHiddenSecrets** method.
1. Run the program and type in the path for our sample image, and record the GPS coordinates in the output.
  ![Ollie the Otter Image](images/OllieTheOtter.jpg)
    * HINT: the path can be relative to the project directory, maybe use the string in the example above :-)
1. Look up the latitude and longitude coordinates in an online map.
1. Screenshot the map and add it into the **images** folder of this project,
1. Last add image markdown below this line to load your map image.

  ![Map Picture](images/Java_Assignment_3_MapPicture.jpg)
## PART 3 - Code Scanning and Interpretation
* Look at the getHiddenSecrets method and identify the following parts:
    * What is the access modifer (public, private, protected)?
  
It's a public method

* Is it a Class method or an object Instance method, how do you know?

It's a Class method because we didn't initiate an instance.

  * What is its return data-type?

It is a "void" type.

  * Does it require any parameters, and if so, how many and of what type?

It requires a "File" type parameter.

* Scan line by line through the code and try to determine how it works?
    * What is familiar to you?

From my observation the method getHiddenSecrets() created a Metadata object with the given File type parameter "file". 
It gets the directories and tags, and it formats the output by the Name, tagName, and the Description. 
The try statement is there in case there are any errors in processing the Metadata. 
The program I wrote asks for the user to enter a file path, and it calls the getHiddenSecrets() method and inputs the file path.

  * What is not familiar to you?

I'm not at all familiar with processing metadata until now, and there's still so much more for me to learn about it.
I also don't fully understand the syntax of Java yet, and I'm learning to see the distinctions and commonalities between Java and Python.
I am also not as familiar with making code as efficiently as possible yet, and I don't know how to recognize if someone's code is more complicated than it needs to be.
I also am not fully familiar with the logic of computers yet, and I don't fully comprehend the process of planning a coding project or designing the systems architecture yet,
which is something I really want to learn.

  * Do the **for** loops make sense, and if so, tell me what you think they do?

As a beginner, my understanding of for loops are that they repeatedly execute code by iterating through the elements of a list.
As an example, a for loop could print each element of a simple list of integers like [1,2,3,4,5,6,7,8,9,10] by printing each element one after the other.

I think I'm familiar with the concept of how for loops work, but I still have so much more to learn about them from a First Principles perspective.

## PART 4 - Turn in
### Same as the last 2 Weeks!
* When completed, use your IDE to commit your Fall-2022 branch back to your GitHub Account's, Java-Assignment-003/Fall-2022 repo/branch.
* From your GitHub account's branch's page, issue a New pull request from your *Fall-2022* branch to the instructor's *Fall-2022* branch and save the *Pull Request URL*.
* Respond to this assignment with the Pull Request URL.
