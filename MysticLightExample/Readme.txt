Possible (known) errors:
	- BadImageException
		Solution: use the other .dll provided by MSI (there is a _x64 one and a normal one). Rename this
					dll to 'MysticLight_SDK.dll'
	- DLL not found
		Solution: if no path is provided, make sure the correct dll is put next to the executable file.
					(default is under the bin/ directory)