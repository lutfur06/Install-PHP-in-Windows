# Install-PHP-in-Windows

1. Download PHP
		https://windows.php.net/download

2.  Download 
![[Pasted image 20240831044721.png]]

3. Unzip and rename folder as php
4. Cut this folder and paste in Program Files
5. Go to `edit the system environment variables`
6. Go to `environment variables`
7. Double click in `path` of `system variables`
8. write `C:\Program Files\php`
9. Then ok it
10. Then ok it, it may be at the end of screen, if ok is not found reduce screen resolution
![[Pasted image 20240831045409.png]]
11. check in terminal using `php -v`
	1. It will show php version information, if nothing show
	2. Run php.exe, it will show the error.
	3. If the error calls `vcruntime140.dill is not found`- need to install C++ visual redistributable
	4. To download this, search C++ windows download
	[Latest supported Visual C++ Redistributable downloads | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)
12.  Change in php.ini file
	1. Rename 
