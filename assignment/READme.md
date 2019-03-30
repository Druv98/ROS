# Publishing and subscribing to msgs

**What are msgs?**
msgs are just simple text files with a field type and field name per line.msg files are stored in the msg directory of a package, and srv files are stored in the srv directory.

In this project I have created a node Velocity which is subscribed to "turtle1/cmd_vel" topic. It listens to the topic and filters out the data and then publishes the data to "turtle1/pose". 


## Authors

* **Druvang wagh** - [Druv98](https://github.com/Druv98)

## Acknowledgments

* ROS Documentation
* Anis Kouba

