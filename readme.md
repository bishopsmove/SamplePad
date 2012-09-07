SamplePad
========

Notepad for Android, based on Google Notepad sample app/tutorial for tablets.

### Support for API 8
   The original sample app, which didn't actually work "out-of-the-box" for me, was set for API 13 (Honeycomb). The problem seemed to be
   derived from an issue with the Clipboard Manager in API 13. The Clipboard Manager was removed to allow a lower MinApiLevel (8), making 
   it compatible for phone use. Cut/Copy/Paste functionality still works, relying on OS API features available from API 8.
   
### Future efforts
   To improve what's here, I will be looking at ActiveSync integration for Outlook and possible OneNote integration, with similar functionality to 
   JumpNote.
   


### Based on work by:

 - Google Sample App, http://developer.android.com/tools/samples/index.html
