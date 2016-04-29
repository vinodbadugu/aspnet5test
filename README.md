# aspnet5test
When I am trying to debug asp.net 5 application in Visual Studio 2015, I am getting following error
"An error occurred attempting to determine the process id of the DNX process hosting your application"

I am able to run using "web" option in Visual Studio 2015, but the error is happening with IIS Express. When I hit ctrl+F5 (run without debugging), the browser window opens and just sits there doing nothing (cursor spins forever).

The Output -> Debug window is empty, so not sure what is the root cause of this error. Not sure if there is anywhere else I have to look.

I have 

Visual Studio 2015 Update 2 

Windows 10 pro v1511 OS build 10586.218 

DNVM 1.0.0-rc1-15540


I even tried dnvm upgrade, which upgraded dnx to dnx-clr-win-x86.1.0.0-rc1-update2

