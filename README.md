# arwin -- Visual C++ Project

Really did not change anything of the original <a href="http://www.vividmachines.com/shellcode/arwin.c">arwin</a>, the win32 address resolution program by steve hanna v.01. 

The main purpose is to provide a Visual Studio project so that people can compile it under their own environment.

Usage: arwin <Library Name> <Function Name> <br>
  Library name: no need to use the .dll extension

Examples: <br>

c:\Workshop>arwin ws2_32 WSASocketA <br>
arwin - win32 address resolution program - by steve hanna - v.01 <br>
WSASocketA is located at 0x764b7140 in ws2_32 <br>

c:\Workshop>arwin kernel32 CreateProcessA <br>
arwin - win32 address resolution program - by steve hanna - v.01 <br>
CreateProcessA is located at 0x75712da0 in kernel32
