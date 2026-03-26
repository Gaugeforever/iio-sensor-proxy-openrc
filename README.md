# iio-sensor-proxy-openrc
OpenRC init script for iio-sensor-proxy.
## Installation
* Clone the repository.
* Move the file to /etc/init.d/
  ```bash
  sudo mv iio-sensor-proxy-openrc/iio-sensor-proxy /etc/init.d/
  ```
* Add the service
  ```bash
  sudo rc-update add iio-sensor-proxy default
  ```
* Start the service
  ```bash
  sudo rc-service iio-sensor-proxy start
  ```
