# Lab Report 4

In this Lab Report, I am going to document me reproducing the task from the competion. I will begin with Step 4 of the task. 

### Log into ieng6

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%204.png?raw=true)

Keys pressed: `<up><enter>`

The `ssh cs15lwi23arn@ieng6.ucsd.edu` command is what logs me into my ieng6 account, and because I have an SSH key for my account on my Mac, I do not have to enter my password. This command was just recently used, so that is why I only had to press `<up>` once to access it in my history. 

### Clone your fork of the repository from your Github account

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%205.png?raw=true)

Keys pressed: `g i t  c l o n e  <Command-V><enter>`

The `git clone git@github.com:igerth/lab7.git` command clones my fork of the repository `lab7` in my GitHub account. I had to type `git clone` out and the `<Command-V>` shortcut pasted my GitHub repo link that I had copied. 

### Run the tests, demonstrating that they fail

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%206.png?raw=true)

Keys pressed: `c d  l<tab> <up><up><up><up><up><up><up><enter>, <up><up><up><up><up><up><up><enter>`

First, I had to `cd` into the `lab7` directory. Then, the `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` command was seven up in my history, so I used the up arrow to access it. Last, the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` command was seven up in my history, so again I used the up arrow to access it. 

### Edit the code file to fix the failing test

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%207.png?raw=true)

Keys pressed: `n a n o  L<tab> .j<tab><enter>, <down> (42 times) <right> (12 times) <delete>, 2, <Ctrl-o><enter>, <Ctrl-x><enter>`

The `nano ListExamples.java` command opens the file from the command line inorder to fix the bug in the code. I used tab-complete to complete the `nano` argument, but since there are both `ListExamples.java` and `ListExamplesTests.java`, it tab-completed to only `ListExamples`. So I typed in `.j` to then tab-complete to `ListExamples.java`. Once inside the `nano` text editor, I pressed `<down>` 42 times and `<right>` 12 times to get to where I needed to edit. I deleted with `<delete>`, typed `2`, and then saved and exited with `<Ctrl-o><Ctrl-x>`. 

### Run the tests, demonstrating that they now succeed

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%208.png?raw=true)

Keys pressed: `<up><up><up><enter>, <up><up><up><enter>`

Just like before, the `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` command was now three up in my history and the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` command was three up in my history. I used the arrow keys for this. 

### Commit and push the resulting change to your Github account

![Image](https://github.com/igerth/Cse15l-lab-report-4/blob/main/lab%207%20step%209.png?raw=true)

Keys pressed: `g i t  a d d  L<tab> .j<tab><enter>, g i t  c o m m i t  - m  "updated" <enter>`

To add and commit, I used `git add ListExamples.java` and `git commit -m "updated"`. I typed out `git add` and then pressed `L` and `<tab>` to tab-complete to `ListExamples`, followed by `.j` and `<tab>` to tab-complete to `ListExamples.java`. I typed out the whole `git commit` command.  

