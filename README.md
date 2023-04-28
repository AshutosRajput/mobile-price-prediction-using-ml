Mobile Price Range Prediction:

Data Description:

The Dataset consists of 22 Columns of which 21 columns are independent and 1 column is dependent.

Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has Bluetooth or not

Clock_speed - the speed at which the microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera megapixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of the mobile phone

N_cores - Number of cores of the processor

Pc - Primary Camera megapixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in MegaBytes

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - the longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Price_range - This is the target variable with values of 0(low cost), 1(medium cost), 2(high cost), and 3(very high cost).

Model prediction Predicting mobile price range using supervised Machine learning classification technique. The dataset tells that it is multiple classifications in nature.

I used some ML models which is very helpful in predicting classification algorithm ex. KNN, SVM, and GuassianNB.



Here I did EDA first in which I checked the correlation and plotted some graphs using matplotlib. And then applied some of the needed algorithms which are Gaussian Naive Bayes, K Nearest Neighbors, and Support Vector Machine.

**Conclusion**

1.From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.

2.half the devices have Bluetooth, and half don’t

3.there is a gradual increase in battery as the price range increases

4.Ram has continuous increase with price range while moving from Low cost to Very high cost

5.costly phones are lighter

6.RAM, battery power, pixels played more significant role in deciding the price range of mobile phone

7.After using many classification techniques we get to know that the K-nearest neighbors and Support Vector Machine gives us the good accuracy.
