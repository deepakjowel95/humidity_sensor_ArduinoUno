# humidity_sensor_ArduinoUno
 Interfacing a Humidity sensor(DHT11) with Arduino Uno to collect Real time data(humidity,temperature,heatindex) from the MCU.
# Instruments/devices required->
 Arduino Uno, Humidity sensor(DHT11|DHT22|DHT23), Bread Board, resistor(10kohm) and jumper wire.
#
# There are different types of humidity sensor available in the market to work with I have mentioned three of those above. Any Humidity sensor of the family of DHT can be utilized   for this project. I have uses DHT11 for this project.
# Procedure
 Step.1-> Open Arduino IDE go to 'tools' on the menu toolbar select 'Manage Libraries..' from the pop down list or you can simply press ctrl+alt+I. In the library manager dialoge   box search for 'DHT'. Install 'DHT Sensor Library ' by adafruit from the search results, there are many libraries available but i have used the one by adafruit for this   project.Once you have clicked on install the library manager suggests you the install a necessary utility library, install that too. 
 
 Step.2->Download the code in the respository and follow the steps as in the comments. Please make sure you read the comments before starting with this project as it will help you to understand the project and make favorable changes to it.
 
 Step.3->Once the above two steps have been performed correctlly, open the 'Serial Monitor' from 'Tools' on the menu toolbar the updates of the temperature,humidity and heat index will be provided after every 2 seconds.Make sure to select the suggested 'Port' before you open 'Serial Monitor' as the IDE tends to refresh it after compilation or upload. Changes can be made in the code to recieve these updates early as well as delayed.
# Connections are to made as shown below in the schematic diagram

![image](https://user-images.githubusercontent.com/51018258/119387785-0c9cc500-bce7-11eb-9f47-d4b754293c24.png)

