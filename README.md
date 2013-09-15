# ioUrTded v1.35
Server binary for [Urban Terror](http://www.urbanterror.info) **4.1.1**

For more details see the ioquake3 [README](https://github.com/urthub/ioUrTded/README) and the ioUrbanTerror [README](https://github.com/urthub/ioUrTded/blob/master/ioUrbanTerror_README.txt).

## Modifications
- Customize server messages with prefixes
- Support of 64 player slots
- Bug fixing: 
	- Flood protection bugfixes
	- DRDoS exploit bugfix
	- Calculation of challenge ping bugfix
	- Console flood bugfix
	- ut_radio buffer overflow exploit bugfix
	- RCON denial of service attack bugfix
	- Callvote exploit bugfix
- Update of masterserver name
- Fixed code and removed compiler warnings


## Compilation
### Linux 32-bit
  1. Install gcc: `apt-get install gcc`
  2. Change to the directory containing this readme
  3. Run `make`

### Linux 64-bit
  1. Install ia32-libs: `apt-get install ia32-libs`
  2. Add multi-architecture support: `dpkg --add-architecture i386`
  3. Perform update: `apt-get update`
  4. Install gcc: `apt-get install gcc`
  5. Change to the directory containing this readme
  6. Run `make`

### Windows using MinGW
  1. Download and install MinGW and MSys from [http://www.mingw.org/](http://www.mingw.org/)
  2. Open the MSys terminal
  3. Change to the directory containing this readme
  4. Run `make`

### Cross compile
It is also possible to cross compile for Windows under Linux using MinGW.

  1. Install mingw32: `apt-get install mingw32`
  2. Change to the directory containing this readme
  3. Run `sh cross-make-mingw.sh`

## License

ioUrTded is licensed under the GPLv2. For more details see COPYING.txt.