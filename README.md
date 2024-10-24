Here's the edited version of the README file with the important sentences **bolded**:

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
* To set a **main class** in a standard Java project...

---

This version highlights key parts related to the build, distribution, and important instructions for running the application.# **PyPhisher Phishing Attack Documentation**

#### This repository documents my use of the PyPhisher tool to simulate phishing attacks on my own system. I utilized the Gmail and Instagram options provided by PyPhisher.

This README includes all the steps from installation to execution, along with screenshots of each step.

## **Installation**

Follow these steps to set up PyPhisher:

```bash
git clone https://github.com/KasRoudra/PyPhisher.git
cd PyPhisher
pip install -r requirements.txt
