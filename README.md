# getpb<br>

Ever needed to quickly read a PKGBUILD for an official repo package?<br>
<br>
Getpb prints PKGBUILD and optionally SCRINFO for official, AUR, and VCS AUR packages. <br>
<br>
Depends: base-devel wget <br>
<br>
Usage: getpb [Operation] <package-name>            <br>
 Operations:                                       <br>
	-S  = Print SCRINFO                        <br>
	-Sv = Print SCRINFO for VCS AUR packages (Build dep's need installed)  <br>
<br>
