# What is JavaANSIColors?
A Java class for using ANSI colors for text-based programs.

# How Do I Use It?

You will need to create a new object in whatever class you are using, like so:

```java
JavaANSIColors jac = new JavaANSIColors() ;
```

Then, you will need to use it. You don't have to worry about creating a method, because there is already
one built into the file.

Here is an example of how to use it:

```java
public class ANSIColorsExample {
    public static void main(String[] args) {
        JavaANSIColors jac = new JavaANSIColors() ;

        jac.printColoredText("This text is red and prints on a new line", jac.RED, false, true) ; // Notice how for the color, you put <OBJECT>.<COLOR>
        jac.printColoredText("This text is blue, bold and doesn't print on a new line", jac.BLUE, true, false) ;
    }
}
```
