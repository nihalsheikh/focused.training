# Day 1

Necessary Requirements: <br>

| No. | Name | Progress/Installed |
| - | - | - |
| 1. | JDK (java development kit) | Done |
| 2. | Set Environment Path <br> - add the bin path to your path variable | Done |
| 3. | Code Editor: <br> - Notepad++ <br> - VS Code <br> - Eclipse <br> - IntelliJ IDE | Done |

<br>

#### Perform some checks:
- Check if `java` is installed, use the cmd in terminal: `javac`, if this runs, it means java is installed.

#### Running a java file:
- Create a basic java program and run it:
    - create a `hello.java` file and add the following code and save it:
        ```
        class hello {
            public static void main(String args[]) {
                System.out.print("Hello, World!");
            }
        }
        ```

    - To run the above file from terminal, type: `javac <filename>.java`, in this case it is `javac hello.java`.
    - After running the above cmd, a class file will be created, then run another cmd: `java <filename>.java`, in this case it is: `java hello.java`.
    - This will give the output `Hello, World!`.

#### IDE setup:
- Download Eclipse (I used Eclipse).
- This IDE has a java compiler build into it.
- Creating a Java Project in Eclipse:
    - File >> New >> Java Project >> Project Name >> Finish/Create
        - open the Java Project >> Right Click on src >> New >> Class >> Class Name >> Finish
        - Click on the Run button to run the Java Project.


### Java start:

`class`: 
- in Java, everything starts/begins from a class. if you don't have class, the java file won't work.
- we write our code inside this class.
