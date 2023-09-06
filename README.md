# UTF16
 Add UTF16 support to PB strings

Provides 

fullcase folding string compares 

uppercase lower case and titlecase 

Declare.s   StrChr(v.i)
Declare.s   StrRight(string$,len) 
  
Prototype   StrAsc(str.p-unicode)
Prototype   StrLen(str.p-unicode) 
Prototype.s StrMid(str.p-unicode,Position,Length)
Prototype.s StrLeft(str.p-unicode,len) 
Prototype   StrCmp(str.p-unicode,b.p-unicode,mode=#CASEFULL) 
Prototype   StrCmpTK(str.p-unicode,b.p-unicode,mode=#CASEFULL) 
Prototype   StrIsUTF16(str.p-unicode) 
Prototype   StrUCase(str.p-unicode)   
Prototype   StrLCase(str.p-unicode) 
Prototype   StrTCase(str.p-unicode,sep=' ')   

