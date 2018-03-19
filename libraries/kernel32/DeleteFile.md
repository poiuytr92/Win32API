
## Function name : DeleteFile
Group: File Management - Library: kernel32    
***  


#### The DeleteFile function deletes an existing file
***  


## Code examples:
[Using the DeleteFile](../../samples/sample_011.md)  
[How to access a file using not its name but an alias (hard link)](../../samples/sample_018.md)  

## Declaration:
```foxpro  
BOOL DeleteFile(
  LPCTSTR lpFileName   // file name
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER DeleteFile IN kernel32;
	STRING lpFileName
  
```  
***  


## Parameters:
lpFileName 
[in] Pointer to a null-terminated string that specifies the file to be deleted  
***  


## Return value:
If the function succeeds, the return value is nonzero  
***  


## Comments:
See also: RemoveDirectory, SHFileOperation, DeleteFileTransacted   
  
***  
