# blazor-native-dialogs

This project demonstrates how to open native HTML dialogs from Nevron Open Vision (NOV), in this case after clicking a NOV button. The idea is to use JavaScript interop to call a JavaScript function that shows a native dialog like this:

```C#
NJsInterop.InvokeVoid("showModal", null);
```

After downloading the project add references to the "Nevron.Nov.Presentation.dll" and the "Nevron.Nov.Host.WebAssembly.dll" from the "Bin\Net80" subfolder of your Nevron Open Vision installation.
