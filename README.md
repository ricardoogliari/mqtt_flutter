# mqtt_flutter

First: I found an interesting article in Medium: Building Real-Time IoT Applications with MQTT in Flutter Web
https://medium.com/@durgeshparekh381/implement-mqtt-in-flutter-web-1d7d954c9cdf

But, the example in this article use a old version of mqtt_client. Then, a made a simple example using flutter web that 
receive a value by mqtt and, change the position of the slider on the screen. 

* Command to publish a mqtt message on terminal: mosquitto_pub -h 'test.mosquitto.org' -t 'test/lol' -m '95'

* mqtt_client package: https://pub.dev/packages/mqtt_client