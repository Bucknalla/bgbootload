This directory should contain two files, neither of which should be checked into any public
VCS repository. If these files are absent, the default CMake setup will look
for them in ../bootload/localdefs

ota_service.txt		should contain one line with the UUID to be used for the service
					advertised by the bootloader when in DFU mode

ota_key.txt			should contain one line with the 256 bit AES key used to encrypt the firmware file, as a hex string.

