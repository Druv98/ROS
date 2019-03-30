# Working with Custom msgs

**What are msgs?**
msgs are just simple text files with a field type and field name per line.msg files are stored in the msg directory of a package, and srv files are stored in the srv directory.

In this project I have created a custom message called IoTSensor.msg which consists of 4 fields(ID,name,temperature and humidity). This message is then published by the node IoT_publisher. I have created another node IoT_subscriber which subscribed IoT_publisher topic.


## Authors

* **Druvang wagh** - [Druv98](https://github.com/Druv98)

## Acknowledgments

* ROS Documentation
* Anis Kouba

