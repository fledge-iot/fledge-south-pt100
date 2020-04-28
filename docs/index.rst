.. Images
.. |pt100_1| image:: images/pt100_1.jpg

PT100 Temperature Sensor
========================

.. image:: images/pt100.jpg
   :align: left

The *fledge-south-pt100* is a south plugin for the PT-100 temperature sensor. The sensor connects via the I2C bus on GPIO pins.

.. note::

   This plugin is only available for the Raspberry Pi as it requires to be interfaced to the I2C bus on the Raspberry Pi GPIO header socket.

To create a south service with the PT100

  - Click on *South* in the left hand menu bar

  - Select *pt100* from the plugin list

  - Name your service and click *Next*

  +-----------+
  | |pt100_1| |
  +-----------+

  - Configure the plugin

    - **Asset Name Prefix**: A prefix to add to the asset name

    - **GPIO Pin**: The GPIO pin on the Raspberry PI to which the PT100 is connected.

  - Click *Next*

  - Enable the service and click on *Done*
