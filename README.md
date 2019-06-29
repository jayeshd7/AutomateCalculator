# AutomateCalculator


Note -This Repository is Using GPG signing Commit .

This program will run on Mac machine.

Basic Pre-requisites -

1.Pyhton 3.6
2.Pyhton pyautogui Library
3.you can install via pip install pyautogui
4. to run calc.exe on mac you need to install WINE follow below steps
https://www.wikihow.com/Open-Exe-Files-on-Mac


About Code -

This is very basic code which is using pyautoGui Library.
you need to capture the screen shot of all desktop based application and based on that it is detected and ran.
if you can see 
pyautogui.locateCenterOnScreen(screenShotPath+'/'+'1key.png') 
this will providing a tuple ( co -ordinates)

to launch the calc.exe
I am using subprocess package which is default available.


Note - this Program using PycharmIDE with Python latest version.
