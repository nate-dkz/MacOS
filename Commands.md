# Introduction
Welcome to my GitHub repository! This file contains a collection of useful MacOS commands that I have compiled. These commands are a great resource for anyone looking to improve their productivity and efficiency while working on a Mac. I hope that these commands will be helpful to you. Feel free to browse through the file and use any of the commands that you find useful. If you have any questions or suggestions, don't hesitate to contact me.

<details>
<summary><b><font size="+1">System</font></b></summary>
</br>

Retrieve software version information.

``sw_vers``

Retrieve CPU and disk statistics.

``iostat``

Retrieve system information.

``system_profiler SPSoftwareDataType SPHardwareDataType``

Retrieve data types for the system_profiler command.

``system_profiler -listDataTypes``

Retrieve system security information.

``sudo /usr/libexec/mdmclient QuerySecurityInfo``

Retrieve system device information.

``sudo /usr/libexec/mdmclient QueryDeviceInformation``

Shutdown the system now.

``sudo shutdown now``

Restart the system now.

``sudo shutdown -r now``

Restart the system in 10 mins.

``sudo shutdown -r 10``

</details>

<details>
<summary><b><font size="+1">Processes</font></b></summary>
</br>


Retrieve list of processes using the internet.

``lsof -P -i -n | cut -f 1 -d " " | uniq``

</details>

<details>
<summary><b><font size="+1">Network</font></b></summary>
</br>

Retrieve the upload / download speed of the network.

``networkQuality``
</details>

<details>
<summary><b><font size="+1">Users</font></b></summary>
</br>

Run as the root user.

 ``sudo su``

Run in super user mode.

 ``sudo -s``

Retrieve a list of users who have signed in recently.
 ``lasy``
</details>

<details>
<summary><b><font size="+1">Files</font></b></summary>
</br>

Retrieve size of directories / files.

``du -sh <file>``
</details>

<details>
<summary><b><font size="+1">Software</font></b></summary>
</br>

Check for latest software updates.

``softwareupdate -l``

Install all software updates.

``softwareupdate -iaR``
</details>

