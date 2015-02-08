This is an example of using Web services and network shared variable communication between a MyRIO a Web browser and an iPad (using Data Dashboard)

To use it just change the IP address to your MyRIO's. Then carry out the following: 

1.Right click on the shared library and select "deploy".
2.Right click on the web service "web" and select "publish to application server"
3.Run RT Main.vi
4.Run UI Main.vi
5.Load up a browser and point it to "http://172.16.0.1:8080/web/changevalue?Control=456" where 456 is whatever value you want

At this point you should see both values in the UI and RT loops update to 456.

To use iPad/Android communication download datadashboard and add a "call webservice" link the web service to a control and you should then be able to 
change the values from there too. You could also just access them through html on your own custom web interface.