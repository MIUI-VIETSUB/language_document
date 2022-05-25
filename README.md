**Hi, I'm BHLNK**
*I created this repo for the purpose of helping miui translators localize MIUI VIETNAMESE .*

First we will work on Github and need a Window or Linux environment.

To add your language to an overlay supported by VIETNAMESE, you need to get the original translation (usually the strings.xml file) from the original apk in MIUI.

Take a look at the list of supported apps here, apps that are not on the list you have to contact me directly at telegram @bhlnk.

Ok, let's get started

 **1. Create a directory with the name vs.AppName.apk :** 
> vs -> mean vietsub
> 
> AppName -> app you are translating and it should be in the support
> list

 **2. create  res folder in the newly created folder**

> create more folder values-xx 
> 
> xx -> stands for your language (check here) 

 **3. Copy strings.xml after translating to the value-xx folder**

That's it, let's dive deeper into strings.xml:

    <string name="string_name_of_app">Your Translate</string>

you just need to edit Your Translate , done. Then copy to values-xx 

 **4. Now test whether your translation works or not**
 

	1. Download this repo
	2. Copy Translated folder to extracted folder
	3.  
	    * In Window : 
		    > run in cmd : test.bat vs.AppName.apk 
		* In Linux : 
			> run in terminal : test.sh vs.AppName.apk
	4. If return value is "Your overlay is OK" upload vs.AppName.apk folder to my drive
	

 - [Supported apps list](https://github.com/buihien224/host/blob/main/sp_list.txt) 
