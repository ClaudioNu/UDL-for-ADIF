# UDL-for-ADIF
Notepad++ UDL file to parse .adi files.

This a simple project to facilitate the reading of .adi (ADIF) files using Notepad++.
This format is widely used by the community of Ham Radio operatos to exchange information of contacts.

This born as a personal tool to easily identify the field inside a text file using colors.
By sure you can use your own schema of colours or to remark fiels using bold.

This is the colour schema used.
Blue - Information about the contacted station.
Red -  Information about the station who generated the file.
Purple - Information about contests and generating program.
Orange - Information about  the QSO

Fell free to change the format or to add new fields.

To use:
On Notepad++ go to "Language", then "User Defined Language" and "Define your Language".
Select the "Import" button and select the ADIF_UDL.xml file, close the window "User Defines Language".
Then Select the ADIF format on the "Language" menu option. That it's all!

Note: The UDL formatter rely on spaces to intentify fields, as the ADIF format don't use the space as a separator turned out very hard to be more specific with the format scheme.

Claudio CX8FS


References: 
ADIF Development Group https://adif.org/ 

ADIF 2.x Reference https://adif.org/adif227.htm 

UDL Reference https://ivan-radic.github.io/udl-documentation/ 

Notepad ++ https://notepad-plus-plus.org/downloads/ 
