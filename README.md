
<a href="https://codebeat.co/projects/github-com-heptocat-monkeycrypt-master"><img alt="codebeat badge" src="https://codebeat.co/badges/3c3db0c2-0ec6-4298-93cb-8702dfba2942" /></a>

# MonkeyCrypt

This modest Java Application aims to teach children the basics of (classical) cryptography, try out different encryption types and practice their skills. It was started by a Project-Seminar group of five German students, and is still a work in progress. For more information visit our [website](https://MonkeyCrypt.jimdo.com "MonkeyCrypt Website")
### How can I download MonkeyCrypt?
You can either [download a .jar](https://github.com/PSeminarKryptographie/MonkeyCrypt/releases "MonkeyCrypt's latest release") you can then simply doubleclick on to run, or you can clone and then compile this repository (Main class: Run.java) yourself and be completely up-to-date with the newest version of MonkeyCrypt.
Like with all java programs there are multiple ways to compile this repository.

1.  The best way is to have <a href="https://ant.apache.org/manual/running.html">ant</a> installed. Then you can just go in the directory Monkeycrypt and type

> ~/<your_path>/MonkeyCrypt/$ **ant**

to make a jar file, or

> ~/<your_path>/MonkeyCrypt/$ **ant run**

to run it right away.

2. Manually compile. We still have the issue that texts aren't read into the program if you compile normally, so this is not recommended. However this works without having to aditionally install anything.

> ~/<your_path>/MonkeyCrypt/src/$ **javac Run.java**
>
> ~/<your_path>/MonkeyCrypt/src/$ **java Run**

3. Through an IDE. If you have an IDE like eclipse or NetBeans, you can import the src - file and run it over the IDE. The class you need to run is Run.java

A .jar version is available under *releases* (See that tab on the top). This Beta - release still has a lot of open issues! However it has been created so beginner - contributors can more easily run our program and submit suggestions.

We still have the issue that texts aren't read into the jar version of the program. To make it possible, copy the jar into the repository next to the src folder, and it should work.

### This is so cool! Can I contribute to MonkeyCrypt?
Of course! MonkeyCrypt started off as a school project, but has now been finally released into the codesharing world. We'd especially appreciate help in translating. You can complete the languages we already have or add your own language. Check out our translation issue or Contributing Guidelines for more. If you're interested in contributing to the code, please contact us to let us know what you'd like to work on to avoid redundancies. Help in form of feedback is always appreciated!
