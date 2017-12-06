# Led-Brightness-control-using-MQTT-on-Adafruit-IO
LED brightness control Using MQTT on Adafruit IO Dashboard.
Go to https://io.adafruit.com/ and create an account or sign in Go to View AIO Keys and use your Username and Keys to edit Config.h file. In adafruit IO create new feed (under actions).
Your feed name must match with the feed name in line 27 of the main code (AdafruitIO_Feed*digital = io.feed("digital")) . Create a new Dashboard in Adafruit IO.
Open the dashboard and add new block by clicking on the "+" sign, choose an appropriate block according to your use.(HERE CHOOSE THE SLIDER TO VARY BRIGHTNESS)
Link the block with your Feed.
Thats it. you can now control the LED using the Adafruit IO dashboard.
