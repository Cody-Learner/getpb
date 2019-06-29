# getpb<br>

Getpb is an Arch package information gathering tool for official and AUR packages. 	<br>
											<br>
Depends: base-devel wget								<br>
											<br>
Usage: getpb [Operation] \<package-name\>						<br>
 getpb defaults to printing PKGBUILD							<br>
											<br>
 Operations:										<br>
	-S  = Print SRCINFO								<br>
	-Sv = Print SRCINFO for VCS AUR packages (makedepends need installed)		<br>
	-Md = List makedepends 								<br>
											<br>
