# MAS Programming Assignment 1

Jiayue Meng
This is the demo of a Habit Tracking App.   
This app is developed using Flutter, Android Studio, Firebase, and GitHub.  

## Description  
This is a multifunctional habit-building app that brings a touch of creativity to the world of habit formation. This project was designed not only to assist users in cultivating good habits but also to offer an engaging and fun experience.  

Here's a breakdown of the app's key features and components:   

### Search for Habits:   
At the heart of the app is a powerful search functionality. Users can type in the habits they want to develop in the search bar at the top of the interface. This user input is seamlessly stored in the Firebase Realtime Database, providing users with a convenient way to search for their goals.   

### Tap Count Recording:  
To make the app more interactive and engaging, I've incorporated a "dot" icon ("..") in the upper-right corner. When users tap this icon, the app records the number of taps they make and stores it in the Firebase database. This feature adds a playful element to habit tracking.  

### Categories, Popular Workouts, and Recommendations:  
The app offers users a variety of habit categories to choose from. Whether it's fitness, mindfulness, or productivity, there's something for everyone. In the "Recommended" section, users can discover and explore healthy habits curated by the app. This diversity ensures that users can tailor their habit-building journey to their unique needs and interests. The app includes a "Popular Workout" section that provides a list of workouts along with details like difficulty level, duration, and estimated calories burned. This feature helps users stay motivated on their fitness journey.  

### User-Friendly Interface:   
The app boasts a user-friendly interface with a well-designed search bar, icons, and vibrant colors. The hintText offers guidance in the search bar, making it easy for users to get started.  

### Learning Goals:   
I chose this project because it encompasses different functions such as user input storage and click tracking. Also, the app's diverse layout elements, including both vertical and horizontal arrangements, a refined search bar, and interactive buttons, offered me the opportunity to dive into various coding techniques, design paradigms, and user experience considerations. Lastly, the rich palette of decorations, from hint texts to icons and color schemes, allowed me to learn how to modify the interface and craft an aesthetically pleasing application. This diversity provided an ideal platform for me to explore a wide range of skills and techniques in app development.      

I embarked on this project with the intention of learning and gaining hands-on experience in software development. I wanted to understand the entire app development lifecycle, from creating user interfaces using Dart and Flutter to connecting the app to web services like Firebase. I also learned how to deploy the Flutter app to Android phones. Additionally, I aimed to enhance my familiarity with GitHub for version control and collaboration. In essence, this app is a blend of functionality, aesthetics, and playfulness. It encourages users to embark on their habit-building journey while gaining valuable insights into the world of app development. Through this project, I've not only honed my technical skills but also crafted an application that's both practical and enjoyable to use. It's been a fantastic learning experience, and I look forward to further refining and expanding this app in the future.   

This is the home page of the App.     

![habit_android_screenshot](https://github.com/JiayueMeng/Flutter_Habit/assets/90874903/39ec26ec-07dc-4b28-bac4-780cf26277da)

## References   

Flutter and Firebase Tutorials  
Set up Flutter and Android Studio: https://www.youtube.com/watch?v=VFDbZk2xhO4  
Built this Habit Tracking App based on the tutorial and code in this video: https://www.youtube.com/watch?v=D4nhaszNW4o  
This is the GitHub repository of the tutorial above: https://github.com/mahdinazmi/Flutter-Basics/tree/main   
Set up Firebase CLI: https://www.youtube.com/watch?v=gptBM2CPMQs  
Created a Firebase real-time database and connected it to my App using this tutorial: https://www.youtube.com/watch?v=ok6se5sOthw   
Learned how to store user inputs to my Firebase real-time database: https://www.educative.io/answers/how-to-use-flutter-to-read-and-write-data-to-firebase    
Learned how to make buttons in my App clickable using this tutorial: https://www.codethebest.com/flutter/flutter-gesturedetector-widget-example/  

Debugging Tutorials  
Solved the connection issue between Flutter and the Android emulator: https://stackoverflow.com/questions/61476059/no-devices-in-vs-code-flutter  
Solved the issue that user inputs could not be written into my Firebase real-time database: https://stackoverflow.com/questions/29901935/android-firebase-setvalue-permission-denied  

Deployment Tutorial  
Deployed my Flutter App to https://www.youtube.com/watch?v=E-jIEKWRpns  
