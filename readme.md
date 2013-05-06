SamplePad
========

Notepad for Android, based on Google Notepad sample app/tutorial for tablets.

### Purpose
    When I made the eventual switch from a iPhone to an Android phone (ver 2.3), the one app I missed was the Notepad app. Android 2.3 didn't 
    have a notepad app out of the box, so when I looked for one I saw that Google had one in their Samples area. When I dug into it, I found that it 
    was intended for the tablet-based Android 3.0 (Honeycomb) so this effort was to back the app to an earlier API level, resolve my lack of notepad
    capabilities on my phone and have a healthy respect for Android app development and deployment.

### Support for API 8
   The original sample app, which didn't actually work "out-of-the-box" for me, was set for API 13 (Honeycomb). The problem seemed to be
   derived from an issue with the Clipboard Manager in API 13. The Clipboard Manager was removed to allow a lower MinApiLevel (8), making 
   it compatible for phone use. Cut/Copy/Paste functionality still works, relying on OS API features available from API 8.
   
### Future efforts
   To improve what's here, I will be looking at ActiveSync integration for Outlook and possible OneNote integration, with similar functionality to 
   JumpNote.
   


### Based on work by:

 - Google Sample App, http://developer.android.com/tools/samples/index.html
