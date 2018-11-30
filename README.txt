Instructions for creating a code plug for the AnyTone AT-D868UV for use with the ARROW W8RP repeater.

Install the AnyTone software on your PC.

Run the software and connect the radio to the PC.  Use Device Manager to adjust the COM port speed to the fastest speed possible.

Select Program->Read From Radio.  This step creates a code plug on your PC from the radio.

Select Tool->Export, click "Export All".  If a Save As file dialog pops up, select export.LST  This step
creates the .CSV files in the folder the programming software was installed into from the code plug in the previous step.

Copy (overwrite) the .CSV files created in the previous step with the .CSV files included with this README.txt file

OPTIONAL: download the latest world-wide digital contact list from https://kf5iw.com/contactdb.php
Extract the file to the folder the programming software was installed into. Delete DigitalContactList.CSV 
and rename the new file to DigitalContactList.CSV

Select Tool->Import, select "Import From File List", then select export.LST from the Open dialog.  This may
take several minutes.

In the programming software, set your DMR ID in the left side tree by navigating to Digital->Radio ID List, click on the
example number 9999999 and replace it with the number assigned to you by https://www.radioid.net

Select File->Save to update the code plug file on your PC

Select Program->Write To Radio to write the updated code plug.
A confirmation dialog will pop up, make sure "Digiatl Contact List" and "Other Data" objects are both selected.
This will take several minutes.  It may look like the program has hung, but do not turn off the radio or computer until it is finished!