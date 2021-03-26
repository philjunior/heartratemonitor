# heartratemonitor
This is a university project and is a real time heart rate monitor

This prototype is meant to be used remotely.

The folder named 'proto-hr-webapp' should be used on your local machine that you wish to monitor from.

The foler named 'proto-hr-sensor' should be used on your raspberry pi.

To run the server run the 'server-db.mjs' file this should load up the web application on your device and start running
your database locally.

Connect up your heart rate monitor as shown in the diagram inside the images folder of the 'proto-hr-sensor' file.

Then run the file 'hr-to-db.py' on the raspberry pi.

This requires your devices to be able to communicate accross your local network as we are not focussing on
security so change your firewall settings to allow this.
