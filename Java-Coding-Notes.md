# Chapter 2, Java Fundamentals

## Simple Java Program Example

### 2.1

public class Simple{
    public static void main(String[] args)
    {
        System.out.print("Programming is grate fun!");
    }
}


- This is a simple print program that prints out: Prgramming is great fun!

* Examining Line by line *

public class Simple

This is the beginning of a class definition, serving as a container for the application
- `public`: A Java keyword (must be lowercase) that controls access to the class
  - Makes the class unrestricted and accessible to all
- `class`: Keyword (lowercase) indicating the beginning of a class definition
- `Simple`: The class name chosen by the programmer

{

* This is called a left brace, or an opening brace, and its associated with teh begiining of the class definition. All programming statements that are a part of the class are enclosed in a set of braces.

// Warning! Make sure u have a closing brace for every opening brace in your program.

public static void main(String[] args)

- Known as the method header
- Required for every Java application program
- Contains multiple keywords that define the method's properties

{

* opening brace belongs to the main method.

System.out.print("Programming is grate fun!");

* This is a statement, it tells the compiler to display the string "Programming is grate fun!" on the screen.

        }
}

* This is a closing brace, it belongs to the main method.

- Lets review:

* Java is a case-sensitive language. It does not regard uppercase letters as being the same
character as their lowercase equivalents.

* All Java programs must be stored in a file with a name that ends with .java.

* Comments are ignored by the compiler.

* A .java file may contain many classes, but may have only one public class. If a .java
file has a public class, the class must have the same name as the file. For instance, if
the file Pizza.java contains a public class, the class's name would be Pizza.

* Every Java application program must have a method named main.

* For every left brace, or opening brace, there must be a corresponding right brace, or
closing brace.

* Statements are terminated with semicolons. This does not include comments, class
headers, method headers, or braces.

**Output:** Programming is great fun!

## Program Structure Breakdown

### 1. Class Header

## Key Java Rules to Remember

1. **Case Sensitivity**
   - Java is case-sensitive
   - Uppercase and lowercase letters are treated as different characters

2. **File Naming**
   - All Java programs must be saved with `.java` extension
   - Example: `Simple.java`

3. **Class and File Relationship**
   - A `.java` file can contain multiple classes
   - Only one class can be declared as `public`
   - The public class name must match the file name
   - Example: `Pizza.java` must contain public class `Pizza`

4. **Program Structure**
   - Every Java application requires a `main` method
   - Statements must end with semicolons
   - Semicolons not required for:
     - Comments
     - Class headers
     - Method headers
     - Braces

5. **Comments**
   - Comments are ignored by the compiler
   - Help document and explain the code

#### 2.2 The print and print ln Methods, and Java API