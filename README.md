# BloX Mosaic-X5

The BloX Mosaic-X5 is based on the [mosaicHAT](https://github.com/septentrio-gnss/mosaicHAT) which is equipped with a [Septentrio Mosaic-X5](https://www.septentrio.com/en/products/gnss-receivers/receivers-module/mosaic). The BloX uses the [ROS driver](https://github.com/septentrio-gnss/septentrio_gnss_driver) maintained by Septentrio.

## Conection

Connect to the modules UI via http://10.99.11.1/septentrio or to the ROS UI via http://10.99.11.1/

## Data

The BloX Mosaic-X5 publishes localization data as [sensor_msgs/msg/NavSatFix](http://docs.ros.org/en/lunar/api/sensor_msgs/html/msg/NavSatFix.html).

