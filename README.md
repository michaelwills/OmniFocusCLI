NAME: OmniFocusCLI
AUTHOR:	Don Southard aka. @binaryghost

CHANGELOG:

**[ 5/27/2011 09:51:32AM version 1.2 ]**

-Started adding DUE DATES!!! This was tricky because I didn't want to mess up start dates. Now you can just type "due" followed by a number of days, weeks or months!

i.e. Mow the grass due 1w

...or... Pull the weeds 2d @Home due 3d (creates a task with a start date of 2 days and a due date of 3 days, plus a context of @Home)

[ 5/26/2011 04:17:43PM version 1.1.1 ]

-Fixed a bug in the hidden due date feature that I do not like. I'm going to officially support due dates eventually.

[ 5/26/2011 12:30:42PM version 1.1 ]

I know this is a big jump in version numbers but I basically rewrote atleast half the code. 

-OmniFocusCLI now reads in your root Contexts directly from OmniFocus in REALTIME! Change your contexts and OmniFocuCLI will still work! This is a major advancement. Contexts are no longer required to start with an @ symbol. Sub-contexts are still not supported but should be soon. This feature may break if OmniGroup ever changes the schema of their database so obviously there are no guarantees. It was also ONLY tested on a Mac App Store version of OmniFocus.

-How the task name was originally created was garabage and I completely rewrote it so it is optimized and more intelligent. 

-Misc bug fixes

[ 5/24/2011 04:19:33PM version 1.0.2 ]
-detection for NULL tasks from the Terminal (Alfred doesn't let you anyway) to prevent blank tasks from being created

[ 5/20/2011 03:02:41PM version 1.0.1]
-Fixed a bug with blank start dates setting "Today" value
-Added "Noon"/"noon" support


INSTALL:

Start by downloading the latest version of OmniFocusCLI from this link to its GitHub Repo: [OmniFocusCLI](https://github.com/binaryghost/OmniFocusCLI/zipball/master)

Inside this zip folder is the OmniFocusCLI.sh script. Extract it to a location of your choice.

Create a new Terminal / Shell shortcut in Alfred.

**Mine looks like this:**

**Title:**_ Add Task to OmniFocus_

**Description:**_ ..._

**Keyword:**_ task_

**Command:**_ /Users/YOU/LOCATION_OF_SCRIPT/OmnifocusCLI.sh {query}_

Do not check the boxes for Quotes or Spaces

Click save.

On the main Terminal / Shell Shortcuts screen, check the box for Silent but leave the box for Action blank.

At this point, you should be able to test your OmniFocusCLI script from Alfred and it should work.

If it doesn't, it is probably because the script does not have permissions to execute on your computer.

To fix this, simple fire up the Terminal. Browse to the location of your script and execute:

**chmod +x OmniFocusCLI.sh**

The next time you try to add a task, it should work fine!

MORE INFORMATION:

Please visit [DirtDon.com](http://www.dirtdon.com/?p=963)

To submit bugs or feature requests please email [support@dirtdon.com](mailto:support@dirtdon.com)

