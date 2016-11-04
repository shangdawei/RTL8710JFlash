# RTL8710JFlash
## JFlash Project for RTL8710

```c
InitStep6_Action = "Write 32bit"
InitStep6_Value0 = 0x1FFFFFF0
InitStep6_Value1 = 0x00000100
InitStep6_Comment = "Write Page Size"

InitStep7_Action = "Write 32bit"
InitStep7_Value0 = 0x1FFFFFF4
InitStep7_Value1 = 0x00001000
InitStep7_Comment = "Write Sector Size"

InitStep8_Action = "Write 32bit"
InitStep8_Value0 = 0x1FFFFFF8
InitStep8_Value1 = 0x00010000
InitStep8_Comment = "Write Block Size"

InitStep9_Action = "Write 32bit"
InitStep9_Value0 = 0x1FFFFFFC
InitStep9_Value1 = 0x00000010
InitStep9_Comment = "Write Block Count"
