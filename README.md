NAME: OmniFocusCLI
VERSION: 1.0.1
AUTHOR:	Don Southard aka. @binaryghost

CHANGELOG:

	[ 5/24/2011 04:19:33PM version 1.0.2 ]
	-detection for NULL tasks from the Terminal (Alfred doesn't let you anyway) to prevent blank tasks from being created
	
	[ 5/20/2011 03:02:41PM version 1.0.1]
	-Fixed a bug with blank start dates setting "Today" value
	-Added "Noon"/"noon" support


For more information, please visit [DirtDon.com](http://www.dirtdon.com/?p=963)

To submit bugs or feature requests please email [support@dirtdon.com](mailto:support@dirtdon.com)

INSTALL:
OmniFocusCLI Install Guide:

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

