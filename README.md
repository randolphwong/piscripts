btscript
--------
Creates a rfcomm device and binds a remote bluetooth device to it.

How to use btscript:

1. Download the file.
2. In terminal, cd to btscript file.
3. chmod +x btscript
4. sudo mv btscript /usr/local/bin
5. type btscript to run the script.
6. Enter the MAC address of your bluetooth device when prompted to do so.
7. Done. You're ready to establish connection with the device.

startup
-------
Schedule a Python file to be run at start up.

How to use startup:

1. Follow step 1 to 4 of btscript (using startup instead)
2. Create a directory: /home/pi/for-startup
3. Place the Python file in the directory
4. Run the startup script in terminal and enter the Python file name.

clearstartup
------------
Clear all Python files scheduled to be run at start up.

How to use clearstartup:

1. Follow step 1 to 5 of btscript (using clearstartup instead)

