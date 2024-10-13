# sc-ptc-control-v2

# lib

- [Mediapipe Tasks Vision](https://cdn.jsdelivr.net/npm/@mediapipe/tasks-vision@latest/)
- [SignTool](https://learn.microsoft.com/en-us/windows/win32/seccrypto/using-signtool-to-sign-a-file/)

```shell
signtool sign /f MyCert.pfx /fd SHA256 /tr http://timestamp.digicert.com /td SHA256 /v MyControl.exe
signtool sign /f MyCert.pfx /p "" /fd SHA256 /tr http://timestamp.digicert.com /td SHA256 /v MyControl.exe
```
