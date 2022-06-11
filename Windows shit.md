KMSPico - Windows activation


Take ownership - https://www.tenforums.com/tutorials/3841-add-take-ownership-context-menu-windows-10-a.html


Uninstalling edge -

```

@echo off

title Uninstalling Edge...

for /D %%I in ("%PROGRAMFILES(X86)%\Microsoft\Edge\Application\*") do "%%~I\Installer\setup.exe" --uninstall --system-level --verbose-logging --force-uninstall

```
