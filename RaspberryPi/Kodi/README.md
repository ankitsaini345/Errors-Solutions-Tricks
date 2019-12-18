# TV doesn't recognize Pi if TV is turned on after PI

My solution is to create an edid,dat when the HDMI channel is connected, and tell the Pi to use it when starting rather than trying to read the device.
sudo tvservice -d /boot/edid.dat
to read the data to a file, and, in the /boot/config.txt,
hdmi_edid_file=1
hdmi_force_hotplug=1