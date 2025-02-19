# Java_Projects

Here is the repository to maintain Java projects for making me noob to pro in Java.

## DailyTasks

This is a simple Java project where you can add a new task every day. Each task is a Java class that prints a message to the console.

### How to Run

1. Compile the project:

   ```
   javac -d out src/main/java/com/example/dailytasks/*.java
   ```

2. Run the project:
   ```
   java -cp out com.example.dailytasks.Main
   ```

### Adding a New Task

1. Create a new Java class in the `com.example.dailytasks` package.
2. The class should extend the `TaskTemplate` class and implement the `execute` method.
3. Add a call to the new task in the `Main.java` file.
