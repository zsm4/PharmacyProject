This is everything that goes in the www part of the cordova file.

To get up and running.
	-open command prompt
	-run "cordova create PharmacyProject edu.pitt.PharmacyProject PharmacyProject"
	-move into new PharmacyProject folder
	-run "cordova platform add android"
	-run "cordova plugin add https://github.com/katzer/cordova-plugin-local-notifications"
	-copy everything in this directory into PharmacyProject/www/
	-run "cordova build"
	-goto PharmacyProject/platforms/android/build/outputs/apk
	-copy android-debug.apk into genymotion
	-Have fun coding!


Task Board
Done:
	-Display medication list and schedule for each medication
	
ToDo:
	-Receive updates through a web service (every 1 min check json for new medications) 
	-Keep track of non-compliances(save non-compliances in local memory and when there are 3 add to json)
	-Display non-compliance warnings(alert user of noncompliances)
	-Send non-compliance notifications to provider and pharmacy(this will just be adding non-compliance to json)
	-Give users the ability to manually add/remove medications (no updates)
		-add medication to JSON
	-Display surveys (survey questions will be provided)
		-not sure about this
	-Beautify the UI
