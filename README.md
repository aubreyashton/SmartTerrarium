# SmartTerrarium

Last edit: 2.26.20
Project Members:
Aubrey Ashton
Rosemary Pedregon
Joseph Shandera

Project Brief Description:
The Smart Terrarium will take sensor measurements and provide these to the user through a lit display and a cellphone application. The Terrarium will also automatically water the plants based on the desired soil moisture levels set by the user in the phone app. 

Making these features work will require the following functions to be coded:
1. Taking Soil Moisture Readings (three times, one for each planter),
2. Taking Temperature Measurement, 
3. Taking Ambient Light Measurement,
4. Using a WiFi Boosterpack to upload these measurements to Firebase,
5. Downloading the user's soil moisture levels settings for each planter from Firebase,
6. Regularly comparing Soil Moisture Readings again the desired Soil Moisture levels and actuating the solenoid valve for that planter to open and allow for the plant to be watered,
7. Recognizing when soil moisture levels have not changed after attempting to water a certain number of times; displaying that the water reservoir needs refilled when this is true,
8. LCD Display with user input (button toggle) to go between the recordings that were uploaded to the app. 
