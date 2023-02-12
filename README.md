# Ghidra-ESP8266

Works fine with Ghidra 10.0.2 and https://github.com/yath/ghidra-xtensa.

Build like:
`gradle -PGHIDRA_INSTALL_DIR=/mnt/d/Software/ghidra_10.0.2_PUBLIC`
Always full path to ghidra dir, and gradle version 6+

Then copy zip file from `dist` folder to `ghidra_10.0.2_PUBLIC/Extensions/Ghidra`, start ghidra and enable extension from File->Install Extensions...
