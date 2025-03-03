 What is rsyslog?
rsyslog is a system that collects and manages log messages from different parts of your computer. Think of it as a logbook where your system writes down everything that happens, such as login attempts, errors, warnings, and system updates.


What is journalctl?
journalctl is a modern logging tool that works with systemd, the process manager of Linux. Unlike rsyslog, which stores logs in plain text files, journalctl keeps logs in a binary format, making it more efficient and powerful.

🔹 Example of journalctl in action:
If you try and fail to log in, journalctl can help you find out why.
If your system is running slow, journalctl can show recent errors and warnings.

/bin → Stores important programs (commands) that everyone can use.
/boot → Contains files needed to start (boot) the computer.
/dev → Stores device files (like hard drives, USBs, and other hardware).
/etc → Contains system settings and configuration files.
/home → Stores personal files for each user (like Documents, Downloads).
/lib → Holds shared libraries (like helpers for programs).
/media → Used for removable media (like CDs, USB drives).
/mnt → A place where temporary storage (like extra hard drives) can be used.
/opt → Stores extra software that is not part of the main system.
/proc → Shows system information (like CPU, memory, and running processes).
/root → The home folder for the root (admin) user.
/run → Stores temporary files for running programs.
/sbin → Holds system programs (used mostly by administrators).
/srv → Stores data for services (like web servers).
/sys → Shows information about the computer's hardware and system.
/tmp → Stores temporary files that get deleted after a while.
/usr → Contains software and system resources.
/var → Stores files that change often, like logs and printer queues.
