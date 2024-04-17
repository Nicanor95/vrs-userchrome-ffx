<h1 align=center>Vrs's Firefox Compact Userchrome</h1>

A userchrome for firefox, it's compact and has tabs instead of buttons.
I'm building this one from zero, *it is not complete*, but it does what I want for now.

## How to use

**1.** Unlock custom css usage.
`about:config` > `toolkit.legacyUserProfileCustomizations.stylesheets` > `true`

**2.** Find your profile folder ('profile names are different for everyone').  
`about:support > Profile Folder > Open Folder`  
or `about:profiles > Root Directory > Open Folder`  

**3.** User styles belong into `\chrome\` folder. Create it, if there is none yet. It should look like this afterwards:  
`\ PROFILE FOLDER NAME \chrome\` 

**4.** Copy `userChrome.css` into `\chrome\` folder.