# Blind-Eye
An Android-based system offers real-time location tracking and smart calling for the visually impaired, along with a Currency Recognition System using Google's Teachable Machine to identify Indian currencies, enhancing their daily lives.

# Proposed Solution
Helps the blind folks in recognizing the Indian Currencies.

Helps them by recognizing the text from images or document.

Using vocal commands, Blind Folks would be able to call their loved ones.

Sends the real-time coordinates of the blind folks to the caretaker.	

# System Flow

![image](https://github.com/Nachiket724/Blind-Eye/assets/63714995/980c89a3-8a72-4a9f-b2f3-3e2286234fb4)

The proposed system consists of two android application, one for caretaker and another for the blind person. Firstly, the caretaker has to create the account in caretaker android application, where the person has to fill his/her details. After registration, he/she has to enter the details of the blind person to use the blind person android application. After the completion of registration, the caretaker has to login into the blind person application. It is the one-time process so that the blind person would be able to use this application. Figure 4 illustrates the working model of the proposed system. After login into the blind person application Google Maps API and GPS (Global Positioning System) fetches the real-time location of the blind person. The real-time coordinates of the blind person are visible on the caretaker application, helps to track the location of the blind person. Thus, if caretaker wishes to know the real-time location of the blind person then the caretaker would able to see the coordinates of the blind person on the map by just opening the application. To remove the difficulties faced by blind folks in recognizing the currency, the proposed model consists of a Currency Recognition System (CRS). The model has been trained on Teachable Machine of Google and generated the TensorFlow Lite model. The model was train with Rs.10 (Old and New Banknotes), Rs.20 (Old and New Banknotes), Rs.50 (Old and New Banknotes), Rs.100 (Old and New Banknotes), Rs.200, Rs.500 and Rs.2000.

# Software Used

Android Studio

Java

TensorFlow Lite

Google Firebase (Cloud)

Firebase Machine Learning Kit

Teachable Machine Learning by Google

Google Maps API

# Screenshots

![image](https://github.com/Nachiket724/Blind-Eye/assets/63714995/ee7c4912-fa3b-4750-8174-4f4961417246)

![image](https://github.com/Nachiket724/Blind-Eye/assets/63714995/3b16713c-72e0-46b4-9137-4072addb54a9)

![image](https://github.com/Nachiket724/Blind-Eye/assets/63714995/c7ab478c-dcf5-49b3-ba9b-88229ba3f0ab)

![image](https://github.com/Nachiket724/Blind-Eye/assets/63714995/6b0f4c06-89e3-479c-b2ca-72bef48c9ee9)






