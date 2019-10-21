# PKISync
This is a modified version of the PKISync.ps1 script provided by Microsoft.  The original script and documentation can be found [here](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/ff961506(v=ws.10)?redirectedfrom=MSDN#BKMK_SavePKISync).  Microsoft's guidance regarding the entire procedure can be found [here](https://docs.microsoft.com/en-us/windows-server/remote/remote-access/ras/multi-forest/configure-a-multi-forest-deployment).

This modifed version includes code to allow for you to import objects into a different forest where there is not a 2 way trust.  The script will prompt for **source forest** and **target forest** crednetials to allow the script to do its work.
