# 1.The CLR’s Execution Model
`jskyzero` `2019/05/17`

## Overview

## Tools & Usage
```powershell
# csc
# 查看支持的语言版本
csc -langversion:?
csc -target:module HelloWorld.cs


# clrver.exe
# display all installed CLR versions
clrver.exe

# dumpbin.exe
# COFF/PE Dumper
dumpbin.exe /all HelloWorld.exe

# ildasm.exe
# Microsoft (R) .NET Framework IL Disassembler

# ilasm
# Microsoft (R) .NET Framework IL Assembler
```