# Lab Report 5 - Week 9

![Image](.jpg)

Hello! Here is my Lab Report 5 - Debugging (by Natasha Tran).


# EdStem Post

**What environment are you using(computer, operating system, web browser, terminal/editor, and so on)?**

I am using a Windows 11 laptop and I am on Visual Studio Code.

**Detail the symptom you're seeing, be specific include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also
great. Avoid saying "it doesn't work'**

When I run my bash script `bash.sh` (which I just type `$ bash bash.sh`, which compiles the `labreport5.java` and checks if it's compiling, I get this error.

```
Java code compiled successfully
Length of the message: 12
Exception in thread "main" java.lang.StringIndexOutOfBoundsException: begin 0, end 13, length 12
        at java.base/java.lang.String.checkBoundsBeginEnd(String.java:4604)
        at java.base/java.lang.String.substring(String.java:2707)     
        at labreport5.main(labreport5.java:9)
```

