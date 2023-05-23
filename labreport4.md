# Lab Report 4 - Week 7

![Image]()

Hello! Here is my Lab Report 4.






**Step 1 - Logging Into ieng6 Account**

![Image](login.png)

From week 7's lab tasks, I didn't need to enter my password after I logged in. Once I typed in `ssh cs15lsp23lg@ieng6.ucsd.edu` into the terminal, I just hit `<enter>` and I was already logged in.

Output - 

![Image](loginoutput.png)






**Step 2 - Cloning the Repository**

![Image](cloning.png)

Since the command for cloning the repository was already in my history, I pressed <up> ten times and then hit <enter>.

Keys pressed: `<up> <up> <up> <up> <up> <up> <up> <up> <up> <up> <enter>`
  
  
  
  
  

**Step 3 - Running the Tests to See Failure**

![Image](cdls.png)

In order to run the tests, I had to first enter the directory for the file. I typed  `ls` and then hit `<enter>`, and then typed `cd lab7` and then hit `<enter>`.

Keys pressed:
`<ls> <enter>`
`<cd lab7> <enter>`

  
  
  
  
  
![Image](javacjava.png)

Next, to run the tests, I typed `<ls>` into the terminal, then hit `<enter>`. After that, I pasted the `javac` and `java` commands using right click and then hitting `<enter>` for each of those commands.

Keys pressed:
`<ls> <enter>`
`<left click> <enter>` (for `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`)
`<left click> <enter>` (for `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`)
  
  
  
  
  
Output: Here, we see that the test is failing.
  
![Image](failureakaoutput.png)



