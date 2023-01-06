# Introduction
This file contains a collection of macOS commands that I have found to be useful. I have gathered these commands in one place as a reference point to refer back to whenever I need them.

<details>
<summary><b><font size="+1">System</font></b></summary>
</br>

Displays software version information.

``sw_vers``

Displays CPU and disk statistics.

``iostat``

Displays system information.

``system_profiler SPSoftwareDataType SPHardwareDataType``

Displays data types for the system_profiler command.

``system_profiler -listDataTypes``

Displays system security information.

``sudo /usr/libexec/mdmclient QuerySecurityInfo``

Displays system device information.

``sudo /usr/libexec/mdmclient QueryDeviceInformation``

Shuts down the system now.

``sudo shutdown now``

Restarts the system now.

``sudo shutdown -r now``

Restarts the system in 10 mins.

``sudo shutdown -r 10``

</details>

<details>
<summary><b><font size="+1">Processes</font></b></summary>
</br>


Displays a list of processes using the internet.

``lsof -P -i -n | cut -f 1 -d " " | uniq``

</details>

<details>
<summary><b><font size="+1">Network</font></b></summary>
</br>

Displays the upload/download speed of the network.

``networkQuality``
</details>

<details>
<summary><b><font size="+1">Users</font></b></summary>
</br>

Runs as the root user.

 ``sudo su``

Runs in super user mode.

 ``sudo -s``

Displays a list of recent user sessions.

 ``last``

Displays information about the current user session.

 ``who``
</details>

<details>
<summary><b><font size="+1">Files</font></b></summary>
</br>

Displays directory size for a file or directory.

``du -h <file>``

Displays file and directory size for all files.

``du -h``

Displays total file and directory size.

``du -sh``

Displays information about a file.

``stat <file>``

Displays the file type for a file.

``file <file>``

</details>

<details>
<summary><b><font size="+1">Software</font></b></summary>
</br>

Checks for latest software updates.

``softwareupdate -l`

Installs all available software updates.

``softwareupdate -iaR``
</details>

