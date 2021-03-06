clamav-daily
============

ClamAV is an open source (GPL) antivirus engine designed for detecting Trojans, viruses, malware and other malicious threats.

The script scans pre-defined system locations depending on the day of the week and sends an email notification with a ClamAV log attached if any malware has been found.

# Installation on Debian Wheezy

The following packages are used by the script:
 
* ClamAV
* Heirloom-mailx
 
To install:

<pre># apt-get install clamav clamav-freshclam heirloom-mailx</pre>

# Configuration

For systems that are up 24/7, you may want to put the script under cron <code>/etc/cron.daily/</code> for a daily execution.
