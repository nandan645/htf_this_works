## Using Netsh command to import proxy settings from Internet Options to WinHTTP.

Before you do this setup your Windows Proxy settings and then follow these steps:

Press Win + X and click on Command Prompt (Admin) and type in `Netsh winhttp import proxy source=ie`

Close the Command prompt and restart your PC
Now the app should recognize your Proxy settings.

In case if you want to reset the Proxy in the command prompt type in the following command and hit Enter: `Netsh winhttp reset proxy`
