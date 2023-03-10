# AmsiBypass-OpenSession
This code bypass AMSI by setting JE instruction to JNE in assembly of amsi.dll file

# Credits :
The original code and idea is from  :  https://github.com/TheD1rkMtr/AMSI_patch

# steps to Run :

1. You can either download the prebuild exe of file from release , or can compile your own with help of solution file
2. after having AmsiOpenSession.exe , run it in powershell with pid of the process , where AMSI will be triggered 
3. we will be setting pid of current process only so , we will run `AmsiOpenSession.exe $pid` 



