Crash Report
============

Crash Report is android project designed to send crash report of the application which run across all versions of Android to developer. When an application crash then it lists a set of email applications to the user to send the crash logs to the developer email.

How to use this:-
-----------------------

Copy the `CrashActivity.java`, `ExceptionHandler.java`, `Helper.java` in your android project. Now write `Thread.setDefaultUncaughtExceptionHandler(new ExceptionHandler(this));` before setContentView in all the activity where your application can crash and finally add activity `CrashActivity.java` in the `AndroidManifest.xml` and add the permission to write the crash logs in the external storage in the `AndroidManifest.xml` 

You can change the developer email in the `CrashActivity.java` on which you want to receive the crash logs.


Developed By
-------------------

    Ajay Saini - ajaysaini.sgvu@gmail.com
    
    

