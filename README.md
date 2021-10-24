TrayToolbar
===

:rocket: Provide the replacement of add new toolbar function that was cancelled in windows 11. 

## Intro

The Windows 10 provide the convenient function that can make the nested folder to be a custom menu. But it was removed in Windows 11. It caused me a lot of inconvenience. When my unhappy reached a critical point, I didn't want to reinstall the Windows 10, so, I wrote this program provided the similar function by system tray.

![windows-10-toobars.png](img/windows-10-toobars.png)

*Nested folder to be a custom menu in Windows 10*



## Guide

### Environment

- Windows 11
- .NET 6.0 ( [Download](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-6.0.0-rc.2-windows-x64-installer) )

## Instruction 

Download released package and then uncompress it. Running "TrayToolbar.exe" to open the app.

Pay attention to the tray icon at taskbar that the new icon showed.

Right-click mouse and click "Options"

![mouse-right-click-menu.png](img/mouse-right-click-menu.png)

*TrayToolbar App & right-click menu*

You can config the parameters of app:

- Path - the folder which you want to be a menu.
- Depth - the maxima scan depth of nested folder. It is recommended not to exceed 5.

![options.png](img/options.png)

*Options*



After config options, restart the app.

Left-click mouse and it shows the nested menu mapping to nested folder.

You can click any item if it is:

- Folder - Open the windows explorer by path.
- Files - Open the file with associated app.

![mouse-left-click-menu.png](img/mouse-left-click-menu.png)

*The nested menu mapping to nested folder*

Enjoy 😁



## Donate 

[BTC]  bc1qd3889yxkk2tqjvxnxwa8qumr068htctat4ef3c

[ETH]  0x19A06db7766758C848787EA56e7C357CaF055B61

If this program help you and willing to sponsor me to continue to improve this software, please support me with effective action.

