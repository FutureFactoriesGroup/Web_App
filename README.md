# Web_App
Files for User Interface


These should all be working, but you will have to edit the file locations for your own computer. As of now, the locations are for the RPi from the lab.

I was not sure about the format of the data, but right now it publishes to the /ordered_item rostopic as a string.

Make sure javascript is enabled in the web browser.

before opening the webpage, do:

roscore in one terminal window and

roslaunch rosbridge_server rosbridge_websocket.launch	in another one (this starts the rosbridge server on the default port 9090)


To test that messages are correctly published to the topic, once roscore is up, type rostopic echo /ordered_item in the terminal window.
Then, navigate to the Item Order page from the Main Menu and choose the options before clicking Order Item Button.
An alert will first pop up to display your choice before this is reflected in the terminal window.


note: Log_In.html has been changed and renamed as index.html
