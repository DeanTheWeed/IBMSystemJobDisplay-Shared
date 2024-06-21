# IBMSystemJobDisplay-Shared
Displays IBM i system information utilizing SQL functions

IBM has created a fairly large and rich set of SQL Functions/Procedures that access system information, such as what subsystems and jobs are active, detailed information about these jobs, object information, library contents, etc. Up until now this information was only available thru system API's, which are difficult at best to use or thru the green screen interface.

With the SQL Functions/Procecures that are available, this information is easily accessible programmatically and can be displayed in any way that makes sense. I started this project as a way to learn more about these Functions/Procedures and to see how easy or difficult it would be to use them. The documentation for the SQL Functions/Procedures is found at "https://www.ibm.com/docs/en/i/7.3?topic=optimization-i-services".  This is for the 7.3 release of the operating system. 

Another purpose of doing this was to find out how easy or difficult it would be to use Visual Studio Code as a development platform. While it isn't as easy as Visual Studio Professional, it is more than capable.  I wrote the web app using the MVC (Model-View-Controller) paradyme. 
