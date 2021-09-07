# osl-rngapi
API For Closeing File Explorer (explorer.exe):
1. Open Notepad
2. Type: 
@echo off
echo Type 1 To Close File Explorer
echo Type 2 To Close This API

set /p number=

if %number% == 1 taskkill explorer.exe cls echo File Explorer Is Now Closed.
if %number% == 2 taskkill cmd.exe
3. On Your Keyboard Do Ctrl+S
4. Save The File As "All Files (.)"
5. Set The File Name To "FileName.bat"
6. Open The File
7. Finished!
