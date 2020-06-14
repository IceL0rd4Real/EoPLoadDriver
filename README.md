# EoPLoadDriver
This is EoPLoadDriver.exe variant that work on 64-bit Windows systems

In order to get this to work, you need to have an system with SeLoadDriverPrivilege token enabled.

And you need to put the following.sys file.
https://github.com/FuzzySecurity/Capcom-Rootkit/blob/master/Driver/Capcom.sys 

Example:
  ./exploit.exe System\CurrentControlSet\custom C:\Users\Capcom.sys
  
 
