# ZoomScripts

This workflow contains 2 scripts for Zoom. *Tested with Zoom Version: 5.2.0 (42634.0805)*


## Leave Zoom
#### Keyword: LZ
This uses Applescript GUI scripting to leave the active zoom meeting.
This Apple script is from Aaron Saray's website (https://www.aaronsaray.com/2020/leave-zoom-with-alfred)


## Dial Into Zoom
#### Keyword: dialin
*Dial-in Setup:* You need to be able to dial phone numbers from your mac to your iPhone. Similar to if you click a phone number in Safari and have the option to "Call using your iPhone" I believe this is by having both logged into iCloud.
The Zoom Phone number is set to San Jose. If you would like to pick a different local number edit the 2nd line of the applescript.

Join the meeting but don't pick computer audio, select Phone Call and you should see a dialog with the dial-in numbers, Meeting ID & Participant ID. This is where you run the workflow. It will pull the meeting and participant Id and dial it on your phone.
