# OSCP-buffer-overflow-prep
So recently, I started off with some basic exploit development, Here is a collection of all the stack overflow exploits I programmed for practicing Buffer OverFlows!


# Steps
* Finding a vulnerable entry point in the program
* Finding the offset
* Controlling EIP
* Finding Bad Characters
* Finding JMP ESP Instruction [Note: If ASLR or any other kind of protection is used in the binary, you might have to bypass them, I haven't learnt that yet]
* Generating shellcode and boom!


# List of programs I exploited till now!
* VulnServer
* FreeFloat FTP Server 1.0
* Server-StrCPY
* CD-To-MP3 Converter 

