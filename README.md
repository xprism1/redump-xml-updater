# Redump XML Updater
## Introduction
Check for the newest .dat files on redump.org and inserts them into a XML file to use with the clrmamepro's _WWW Profiler_ standard. The script can also run a simple local webserver using Python's http.server module, to update the XML into clrmamepro.

## How to use:
1. Install Python 3, and the requests module.
2. Edit the UserInfo.xml file with log-in data (if you have).
3. Run the script, if you chose the first option it will update the XML and start a local server too.
4. Add the following URL into clrmamepro's _WWW Profiler_: `localhost/profile.xml`

## Notes:
* The port should left at 80 as clrmamepro only works with that port.
* The script doesn't insert any links to download the .dat files.
