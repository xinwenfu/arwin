# arwin

Really did not change anything of the original <a href="http://www.vividmachines.com/shellcode/arwin.c">arwin</a>, the win32 address resolution program by steve hanna v.01. 

The main purpose is to provide a Visual Studio project so that people can compile it under their own environment.

Example use

c:\Workshop>arwin ws2_32 WSASocketA
arwin - win32 address resolution program - by steve hanna - v.01
WSASocketA is located at 0x764b7140 in ws2_32

c:\Workshop>arwin kernel32 CreateProcessA
arwin - win32 address resolution program - by steve hanna - v.01
CreateProcessA is located at 0x75712da0 in kernel32
