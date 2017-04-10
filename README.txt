This is everything that goes in the www part of the cordova file.

To get up and running.
	-open command prompt
	-run "cordova create PharmacyProject edu.pitt.PharmacyProject PharmacyProject"
	-move into new PharmacyProject folder
	-run "cordova platform add android"
	-run "cordova plugin add https://github.com/dhjw/cordova-plugin-local-notifications.git"	CHANGED THIS, MAKE SURE TO USE THIS NEW ONE
	-copy everything in this directory into PharmacyProject/www/
	-run "cordova build"
	-goto PharmacyProject/platforms/android/build/outputs/apk
	-copy android-debug.apk into genymotion
	-Have fun coding!


Task Board
Done:
	-Display medication list and schedule for each medication ---- Zach
	-Display non-compliance warnings(alert user of noncompliances) ---- Zach
	-Keep track of non-compliances(save non-compliances in local memory and when there are 3 add to json) ---- Zach
	
ToDo:

	-Receive updates through a web service (every 1 min check json for new medications) ---- Elias
		-background process
	-Send non-compliance notifications to provider and pharmacy ---- Zach
		-Ask Dmitriy about this. Seems server side.
	-Give users the ability to manually add/remove medications ---- Sascha
		-add/remove medications to JSON
	-Display surveys (survey questions will be provided) ---- Adam
		-Ask Dmitriy if you have questions about this
		
	-Beautify the UI ---- If we feel like it
