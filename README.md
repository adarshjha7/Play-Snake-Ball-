

========================  
**Play-Snake-Ball**  
========================  
Its a game developed with 2 main components : 

**Board Class:**
* **This class extends JPanel and is responsible for the game's main functionality, including rendering graphics and handling game logic.**
Game Components:
* **Images**: Loads images for the snake's head, body, and the apple using the loadImages() method.
* **Game State:** Maintains the state of the game, including the snake's position, direction, and whether the game is ongoing.
* **Movement:** Handles the movement of the snake based on user input and checks for collisions with itself or the boundaries of the game area.
* **Ball Location:** Randomly places apples on the board, and if the snake eats an apple, it grows in size.
* **Game Over Logic:** Checks for collision conditions and displays a "Game Over" message when the game ends.
* **Timer:** Uses a Timer to create the game's refresh rate, calling the actionPerformed method at regular intervals.

**SnakeGame Class:**
**This class extends JFrame and serves as the main window for the game.**
* It initializes the **game window**, adds the **Board component**, and makes the window visible.
* Main Method: This is the entry point of the application, where an instance of SnakeGame is created and displayed.



---

========================  
**BUILD OUTPUT DESCRIPTION**  
========================  

When you build a Java application project that has a main class, the IDE automatically copies all of the JAR files on the project's classpath to your project's `dist/lib` folder. The IDE also adds each of the JAR files to the **Class-Path element** in the application JAR file's **manifest file** (`MANIFEST.MF`).

**To run the project from the command line, go to the `dist` folder and type the following:**

```bash
java -jar "SnakeGame.jar"
```

**To distribute this project, zip up the `dist` folder (including the `lib` folder) and distribute the ZIP file.**

**Notes:**

* If two JAR files on the project classpath have the same name, only the **first JAR file** is copied to the `lib` folder.
* Only **JAR files** are copied to the `lib` folder.  
  If the classpath contains other types of files or folders, these files (folders) are not copied.
* If a library on the project's classpath also has a **Class-Path element** specified in the manifest, the content of the **Class-Path element** has to be on the project's runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element....

---
Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

![Screenshot (176)](https://github.com/user-attachments/assets/e6255522-d93a-4159-8456-a905dab92cc7)


