MusicTribeAutoDownload
================
This small python3 script accesses the [Musictribe](https://www.musictribe.com) Website and analyzes the version numbers of your products of interest and downloads them to your harddrive.  
  
Installation on you iOS Device  
====================  
Just copy the python-script to a somehow useable place. Include the MusicTribeAutoDownload.ini configuration file in the same directory as the python script. 
In our case the script runs on a linux machine which is used for other subjects. The crontab runs the python script once each hour.  

Configuration  
===========  
The configuration of the script is configured using the ini-file. This file is structured using sections. 

1. [Global]
1. [Mail]
1. [URL]

The Global section needs on parameter downloadPath which contains a directoy path where the files should be copied to. Subdirectories will be created as neede. A subdirectory for each [Musictribe](https://www.musictribe.com)company that you download files from will be created.

The Mail section contains mail based information. The script needs an email-address and an smtp-server to send out mails each time when a new file has been download. The other could be used to maintain the message text send out to recipients.

The URL settings  contain one ore several urls that should be monitored to download files from [Musictribe](https://www.musictribe.com)download section. The current file contains several examples to download files from the Behringer or Midas Website.
Other Software from [Musictribe](https://www.musictribe.com)
===

This script could be adjusted to observe other software, handbooks, firmware, drivers and what ever you like coming from [Musictribe](https://www.musictribe.com). The companies that are currently part of [Musictribe](https://www.musictribe.com) are

1. [Musictribe](https://www.musictribe.com)
1. [Midas](https://www.midasconsoles.com)
1. [klarkteknik](https://www.klarkteknik.com/)
1. [LAB.GRUPPEN](https://www.labgruppen.com)
1. [lake](https://www.lakeprocessing.com/)
1. [TANNOY](https://www.tannoy.com/)
1. [Turbosound](https://www.turbosound.com/)
1. [tc electronic](https://www.tcelectronic.com/)
1. [TC Helicon](https://www.tc-helicon.com/)
1. [Behringer](https://www.behringer.com/)
1. [Bugera](https://www.bugera-amps.com/)
1. Oberheim
1. [AURATONE](https://www.auratone.eu/)
1. [coolaudio](https://www.coolaudio.com/)
1. [EUROCOM](https://eurocom.musictribe.com/)

Each of those companies (except of Oberheim) offer some kind of downloadable files which will be useful for some of us. I am personally only interested in midas, behringer, klarkteknik and tcelectronic but some of you might be interested in files from the other [Musictribe](https://www.musictribe.com)companies as well. Feel free to ask how to adjust the request-strings for those companies.

Have fun!

