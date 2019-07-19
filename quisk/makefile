
all:
	python3 setup.py build

win:
	C:/Python27/python.exe setup.py build -c mingw32 --inplace --force

winrun:
	C:/Python27/python.exe quisk.py

winmsi:
	C:/Python27/python.exe wix/files.py

wininstall:
	msiexec -i wix\\quisk.msi

winuninstall:
	msiexec -x wix\\quisk.msi

macports:
	env ARCHFLAGS="-arch x86_64" python3 setup.py build -D USE_MACPORTS
