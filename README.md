# Habit-building App

Jiayue Meng    
This is the demo of a Habit Tracking App.   
This app is developed using Flutter, Android Studio, Firebase, and GitHub.  

## Description  
This is a multifunctional habit-building app that brings a touch of creativity to the world of habit formation. This project was designed not only to assist users in cultivating good habits but also to offer an engaging and fun experience.  

Here's a breakdown of the app's key features and components:   

### Authentification  
Users will first go to the login page when open the app, they need to register or log in using their email and password. If he is a new user, he needs to register first, and his account information will be stored in the Firebase database. The email address must be correctly formatted (i.e. xxx@yy.com) and the password must be at least 6 characters. Then, he can log in to the home page using the email and password he sets. When he wants to log out, he can tap the "arrow" icon ("<") in the upper-left corner of the home page.

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

This is the login/register page of the app:    

![login_page](https://github.com/JiayueMeng/Flutter_Habit/assets/90874903/2b9aeeef-2866-4a93-9435-bc00f8d3d08b)

This is the home page of the app:      

![habit_android_screenshot](https://github.com/JiayueMeng/Flutter_Habit/assets/90874903/39ec26ec-07dc-4b28-bac4-780cf26277da)

## Debugging and References   

### Problem Solving
Emulator Compatibility:  
Initially, my app couldn't run on the Android emulator. After a thorough debugging process, I realized that this issue might have been due to a lack of storage on my computer. To resolve this, I switched to another computer with sufficient storage capacity, which enabled me to continue development smoothly.  

Emulator Display Issue:   
I encountered a perplexing problem where both Android Studio and Flutter appeared to work correctly, but the app wouldn't display in the emulator. After careful inspection, I discovered that special characters in the project folder's name were causing this issue. Moving the project to another folder without special characters resolved the problem, allowing the app to display correctly in the emulator.  

Firebase Database Connection:  
The most challenging issue I faced was connecting the app to the Firebase database and storing user inputs. Initially, I struggled with understanding how to integrate Firebase into our Flutter project and write the user inputs or actions to the database. This led to difficulties in implementing the feature of tap recording and searching. To address this, I conducted extensive online research, watched tutorials, and consulted Firebase documentation. This learning process enabled me to successfully write the part of the code to integrate Firebase into my app, store user inputs, and resolve this issue effectively.  

Firebase Database Permission Denied:   
I encountered and successfully resolved an issue related to Firebase Realtime Database permissions. Initially, when attempting to write user inputs to the database, I faced a "Permission Denied" error. This challenge required me to understand Firebase's security rules and permissions structure better. After carefully configuring the Firebase security rules and ensuring that the app had the necessary permissions, I overcame this obstacle. 

### Flutter and Firebase Tutorials  
Set up Flutter and Android Studio: https://www.youtube.com/watch?v=VFDbZk2xhO4  
Built this Habit Tracking App based on the tutorial and code in this video: https://www.youtube.com/watch?v=D4nhaszNW4o  
This is the GitHub repository of the tutorial above: https://github.com/mahdinazmi/Flutter-Basics/tree/main   
Set up Firebase CLI: https://www.youtube.com/watch?v=gptBM2CPMQs  
Created a Firebase real-time database and connected it to my App using this tutorial: https://www.youtube.com/watch?v=ok6se5sOthw   
Learned how to store user inputs to my Firebase real-time database: https://www.educative.io/answers/how-to-use-flutter-to-read-and-write-data-to-firebase    
Learned how to make buttons in my App clickable using this tutorial: https://www.codethebest.com/flutter/flutter-gesturedetector-widget-example/   
Added authentication to the app: https://www.youtube.com/watch?v=rWamixHIKmQ

### Debugging Tutorials  
Solved the connection issue between Flutter and the Android emulator: https://stackoverflow.com/questions/61476059/no-devices-in-vs-code-flutter  
Solved the issue that user inputs could not be written into my Firebase real-time database: https://stackoverflow.com/questions/29901935/android-firebase-setvalue-permission-denied  

### Deployment Tutorial  
Deployed my Flutter App to https://www.youtube.com/watch?v=E-jIEKWRpns   

## Repository and Firebase Database Access  

URL to the GitHub repository: https://github.com/JiayueMeng/Flutter_Habit.git  
Firebase Realtime Database API key: AIzaSyCMPzTWIOTFPk0vtUijRh_szxAkgceH6Yg  
Firebase Realtime Database URL: https://masprogramming1-default-rtdb.firebaseio.com/  
Firebase Authentication: People can only access it by invitation. I can provide access to TAs if needed. 

## Instructions  

### Running on an Android Emulator

1. Clone or download the code for your Flutter project from GitHub.  
2. Ensure you have Flutter and Dart installed on your development machine. Follow the official Flutter installation guide if you haven't already.  
3. Open Android Studio to create and configure an Android emulator if you haven't already. Ensure that the emulator is up and running.  
4. Use your preferred code editor (e.g., Visual Studio Code) to open the Flutter project.   
5. Open a terminal within your project's directory and run `flutter pub get` to install project dependencies.   
6. Make sure the emulator is running, then run the following command to verify connected devices: `flutter devices`. The emulator should appear in the list.  
7. Execute `flutter run` in the terminal. Flutter will build and deploy the app to the Android emulator. You should see your app running on the emulator shortly.  

### Running on a Physical Android Phone  

1. Clone or download the code for your Flutter project from GitHub.  
2. Ensure you have Flutter and Dart installed on your development machine. Follow the official Flutter installation guide if you haven't already.  
3. On your Android phone, go to Settings > About Phone and tap on the Build Number several times (usually 7) until you see a message indicating that Developer Options are enabled.  
4. In the Developer Options section (usually located in Settings > System > Developer Options), enable USB debugging.  
5. Connect your Android phone to your computer via a USB cable. You may need to authorize the computer for USB debugging on your phone.  
6. Use your preferred code editor (e.g., Visual Studio Code) to open the Flutter project.  
7. Open a terminal within your project's directory and run `flutter pub get` to install project dependencies.   
8. Run `flutter devices` in the terminal to ensure that your connected Android device is listed.  
9. Execute `flutter run` in the terminal. Flutter will build and deploy the app to your connected Android device. You should see your app running on your physical phone shortly.

### Revision Control History:  

Commit History: https://github.com/JiayueMeng/Flutter_Habit/commits/main  

During the development of our Flutter project, my partner and I utilized Git for version control to effectively manage our codebase and collaborate on the project. Our Git history and coordination process involved a series of commits, pull requests, code reviews, and deployments.   
We began by discussing the project's requirements and functionality. We decided on the responsibilities of reviewing, deploying, and modifying decorations for each other's project. I initiated the project by creating a Git repository on GitHub and pushed the initial codebase.
My partner cloned the repository to his local machine to start contributing. Regular communication via messaging apps ensured that we stayed informed about each other's progress and discussed any issues we met during development. We followed a commit message convention to make our Git history more descriptive and informative. Each commit included a concise message explaining the changes made. Regular commits helped us track our progress and made it easier to identify and resolve conflicts. Before merging code into the main branch, we conducted thorough code reviews. This involved evaluating each other's code for correctness, code quality, and adherence to project standards. My partner was responsible for testing the app on his computer and devices to ensure it ran smoothly. My partner contributed to the project by making small changes to the interface. Throughout the collaboration, we learned valuable lessons about effective communication, coordination, and the importance of clear and concise commit messages. We also recognized the benefits of code reviews in maintaining code quality. In retrospect, we identified areas where we could improve our collaboration. Better project management tools and documentation could have enhanced our workflow. Next time, we plan to utilize project boards or issue trackers to manage tasks more efficiently and maintain better documentation of project requirements. I also plan to make good use of branches for the following projects when we need more collaborations. 
