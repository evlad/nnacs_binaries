# nnacs_binaries
Neural Networks Applications for Control Systems (binary builds)

# additional software
* tcl/tk 8.6 x86/x64 depending OS version (https://www.activestate.com/products/tcl/downloads/)
* visual studio c++ 2010 redistributable x86 (usually it is vcredist_x86.exe)
* plotchart-2.0.2 (take in this repository)

# configuration
Windows 10:
Open Control Panel -> User Accounts, then click the "link" one the left: Change my environment variables
* NNACSSYSDIR=c:\nnacs
* NNACSUSERDIR=c:\labworks

To run NNACS please execute nnacs.tcl

# file system tree example
```
c:\
  labworks\
    User\
      001\
      002\
      ..
  nnacs\
    bin\
      nnacs.tcl
    labworks\
      Examples\
    lib\
      exfuncs\
    scripts\
    templates\
 ```
