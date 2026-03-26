# iio-sensor-proxy-openrc
OpenRC init script for iio-sensor-proxy.
## Dependencies
* [iio-sensor-proxy](https://gitlab.freedesktop.org/hadess/iio-sensor-proxy/)
## Installation
* Clone the repository.
  ```bash
  git clone https://github.com/Gaugeforever/iio-sensor-proxy-openrc.git
  ```
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
