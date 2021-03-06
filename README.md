# IBM UrbanCode Deploy Git Install Plugin [![Build Status](https://travis-ci.org/IBM-UrbanCode/Git-Install-UCD.svg?branch=master)](https://travis-ci.org/IBM-UrbanCode/Git-Install-UCD)
---

Note: This is not the plugin distributable! This is the source code. To find the installable plugin, go into the 'Releases' tab, and download a stable version.

### License
This plugin is protected under the [Eclipse Public 1.0 License](http://www.eclipse.org/legal/epl-v10.html)

### Compatibility
	The IBM UrbanCode Deploy automation plugin installs Git v1.8.3.4.
	This plugin requires version 6.1.1 or later of IBM UrbanCode Deploy.
    
### Installation
	The packaged zip is located in the releases folder. No special steps are required for installation.
	See Installing plugins in UrbanCode Deploy. Download this zip file if you wish to skip the 
	manual build step. Otherwise, download the entire Git-Install-UCD and 
	run the "ant" command in the top level folder. This should compile the code and create
	a new distributable zip within the releases folder. Use this command if you wish to make
	your own changes to the plugin.

### History
    Version 2
        New Steps
            - Create Repository
            - Migrate Repository

    Version 1
        Community GitHub Release
 
### How to build the plugin from eclipse client:

1. Expand the Groovy project that you checked-out from example template.
2. Open build.xml file and execute it as an Ant Build operation (Run As -> Ant Build)
3. The built plugin is located at releases/Git-Install-UCD-vdev.zip 

### How to build the plugin from command line:

1. Navigate to the base folder of the project through command line.
2. Make sure that there is build.xml file there, and then execute 'ant' command.
3. The built plugin is located at releases/Git-Install-UCD-vdev.zip 
Note: Edit the Build.xml to change the version 'dev' to a release number.
