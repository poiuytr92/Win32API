
## Function name : DllGetVersion
Group: Shell Functions - Library: shell32    
***  


#### Implemented by many of the Microsoft� Windows� Shell dynamic-link libraries (DLLs) to allow applications to obtain DLL-specific version information.
***  


## Code examples:
[Obtaining Shell32.dll version](../../samples/sample_299.md)  

## Declaration:
```foxpro  
HRESULT CALLBACK DllGetVersion(
	DLLVERSIONINFO* pdvi
);  
```  
***  


## FoxPro declaration:
```foxpro  
DECLARE INTEGER DllGetVersion IN shell32;
	STRING @pdvi  
```  
***  


## Parameters:
pdvi
Pointer to a DLLVERSIONINFO structure that receives the version information.
  
***  


## Return value:
Returns NOERROR (0) if successful, or an OLE-defined error value otherwise.  
***  
