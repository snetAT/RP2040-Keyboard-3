RP2040-Keyboard-3

  https://www.waveshare.com/wiki/RP2040-Keyboard-3#Pico_Get_Start_Quick
  
  https://www.zfrontier.com/lab/keyboardTester

  Macro definitions can be found in the HID_Keyboard.h file. Click Ctrl-F12 on #include "Keyboard.h" -> #include <HID_Keyboard.h>

  Switch to Drive Mode "sudo stty -F /dev/ttyACM0 1200" and copy /tmp/arduino/sketches/xxxxxxxx/RP2040-Keyboard-3.ino.uf2 to mounted Folder.
   
