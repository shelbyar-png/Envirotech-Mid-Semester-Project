DIY Environmental Sensor System for T / RH / CO2 Monitoring

The primary goal of this project was to construct an open-source environmental data logger capable of collecting continuous microclimate parameters on an SD card over an extended multi-day deployment. A custom hardware stack was constructed using an Arduino Uno R3 microcontroller interfacing with an Adafruit SHT40 breakout board (high-accuracy digital temperature and relative humidity sensor) and a Sensirion SCD30 module (a true Non-Dispersive Infrared [NDIR] carbon dioxide sensor that also features secondary temperature and humidity sensing). Data storage was handled locally via an SPI-driven MicroSD card breakout board configured to write data to a localized data.csv file file structure.

This project is open-source, and modifications and customizations are encouraged if required. However, any changes made to the design or code are at your own risk.
