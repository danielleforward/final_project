## Summary
The goal of this project is to create a “smart” kitchen scale that records portions of food you've eaten using the difference in weight via a weight sensor. Basically you would set the scale to sync with a particular item (e.g. cereal), then you would take its initial weight by placing the cereal box on the scale. The scale would record the weight data along with the time and date. When you go to eat some of that cereal, you remove the cereal box from the scale, pour some in your bowl to eat, then place it back on the scale. It now has a new weight, and the scale measures that, along with the time and date again. It takes the second weight and subtracts it from the first weight, giving you a portion that you've eaten (in grams), and this would cross with the nutritional data of that cereal, and display the nutritional facts of that portion you just consumed. This data would be tracked over time and visualized in a graph of nutrition data & weight data as outputs. I’d like to be able to scan a barcode for the cereal and have that import its nutritional data into the system, but I don’t know if that’s possible.
	To summarize, the input would be the ‘weight change over time’ of a food item (e.g. cereal) and that food item’s nutritional data (either by scanning a barcode or entering it manually) and the output would be a visualization of the changes in weight data over time multiplied by that nutritional data entered, and therefore the nutrients ingested over time from that item.
	
UPDATE:
Due to extensive calibration of the scale, I was only able to implement the gram specification and nutrient readout via the serial monitor in fiber, sugar, and calories per gram of weight placed on the scale. In future iterations, I would hope to add the cataloging of food data to also determine what was consumed using the difference of the previous variables.

Calibration 1:
https://vimeo.com/148752791

Calibration 2:
https://youtu.be/OegTOj8_KaU


## Component Parts
- Digital kitchen scale (bought off Amazon and hacked)
- Display (computer screen?)
- Cereal
- Barcode scanner to scan the cereal? Can we use my phone or do we need a real barcode scanner from Adafruit?


## Challenges
- Hacking a scale
- The programming
- **Visualizing data**


## Project Timeline
- Week 1: Get the parts, research code/hacks for what I want to do
- Week 2: Do the electronics
- Week 3: Program!
- Week 4: Program!
- Week 5: Program!
