# Summary

On a simple Kotlin with Gradle projet, we import the library "OkHttp".
We make a worksheet that uses a class (OkHttpClient) provided by the library.
We make a scratch file that uses a class (OkHttpClient) provided by the library.

The scratch file allows module selection and auto import the class.

# Issue

The worksheet doesn't allow module selection (if the library is only imported on a specific module).
We can still create in the module folder but I'm not sure if it will work.
The worksheet won't import the class OkHttpClient and there is no way to make it works.

The scratch file works perfectly:
![Scratch](https://raw.githubusercontent.com/NitroG42/WorksheetNoImportNoModule/master/assets/scratch.png)

While the worksheet produces the following:
![Worksheet](https://raw.githubusercontent.com/NitroG42/WorksheetNoImportNoModule/master/assets/worksheet.png)

# Tracker

https://youtrack.jetbrains.com/issue/KT-41687

https://youtrack.jetbrains.com/issue/KT-41684 
