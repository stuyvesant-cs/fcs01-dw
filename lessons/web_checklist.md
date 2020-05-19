---
layout: page
title: Python Website Checklist
---

#### In order for your python code to successfully produce a webpage, the following things must be done:

1. The program must be saved in *public_html* (or a subdirectory of *public_html*).
2. The program must have execute and read permissions in the __user__ and __other__ permission areas. When running `ls -l` the permissions should look like this: `-rwxr--r-x 1 dw dw   83 May 17 17:14 hello.py`. Note that the __group__ permissions (the middle 3), are unimportant for this activity. If the permissions are incorrect you can fix them with `chmod`:
  ```
  $ chmod uo+x hello.py
  $ chmod uo+r hello.py
  ```
3. The first line of the program must be the correct _sh-bang_ invocation:
  ```
  #!/usr/bin/python
  ```
4. The second line of the program should provide the correct MIME type:
  ```
  print ("Content-type: text/html\n")
  ```
5. The program should run via the command line without errors like so:
  ```
  $ ./hello.py
  ```
6. The url should be: __http://moe.stuy.edu/~USERNAME/FILE.py__

#### If you have verified that all of the above are correct, then you should not get an Internal Server Error
