# exam2
run the RPC loop to get input string commands from PC/Python, and it will in turn call custom RPC functions.\
classify the saved accelerator data values with the gesture classification TF Lite model\
mbed will publish the classified gesture as an event (gesture ID and sequence number of the event) through WiFi/MQTT to a broker.\
extract features of the saved accelerator data values\
After the PC/Python gets a preset number of gesture events, it sends a command to mbed to stop the accelerator capture mode.\
After the PC/Python send the stop command, please send another command to retrieve the saved feature data.
