# Azure Function

## Issue: Can't run Azure function in Visual Studio 2022. 

https://stackoverflow.com/questions/70745114/azure-functions-on-net6-0-fail-to-run-locally-with-hostpolicy-dll-error

### Solution: 

The actual fix was to delete the C:\Program Files\dotnet\shared\Microsoft.NETCore.App folder with all the 2.0 files in it. No idea why those were being referenced. – 
