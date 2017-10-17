FM-NavigationFramework
===========
Wouldn't it be nice to have a button bar that you could have on every layout that handles basic navigation of your FileMaker layouts? And by simply rearranging/renaming or adding layouts, your navigation would reflect the changes automatically? 

There have been other solutions over time, although not all have met all requirements that I would want of such a tool. Those would include, in no particular order: 

 • Work in Browse and Find mode. 
 • Use Themes and Styles to modify appearance.
 • Allow manually switching layouts and stay up to date. 
 • Will work with multiple windows.
 • No require any plugins. 
 • No additional schema needed. 
 • Handles an arbitrarily large enough number of layouts. 
 • Uses all native FileMaker objects and functionality. 

Other nice to haves: 

 No custom functions, for portability. 
 Retain the last visited sub-section, for navigating multiple tiers. 

This solution provides all these points and is easy to use in your own FileMaker solutions. Works with FileMaker 14 and up.

Note: If you wish to support multiple windows if a user manually opens another window, you will need to add a script trigger to the "OnWindowOpen" trigger from the File Options dialog.
This is now the default behavior, so will run after the initial script trigger to open the file. It is then unnecessary to run in that script, as it runs in the second script trigger.

Read more here:
https://www.soliantconsulting.com/blog/2017/10/filemaker-navigation-bar