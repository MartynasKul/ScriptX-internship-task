# ScriptX Task

Project made for an internship application process at ScriptX

Project Should be made for android. Coding done on Windows11 machine and tested with Iphone.
As a project itself, it is made with React-Native, used expo for testing and some routing between pages.
Thanks to React-Native, app follows the devices color mode, as in: if device is in dark mode, the app follows and vice versa.
Project has three main features that were supposed to be implemented (pictures will be included in this readme at the bottom):
1. A basic homescreen with a few buttons with my idea of making it personalized,
2. A browse page that lets users browse through movies sepparated by categories. main categories were: least popular, latest and upcomming movies, followed by each genre that TMDB api allowed me to get. this screen allows for vertical scrolling between each category aswell as horizontal scrolling within categories to browse movies
3. A movie details page, that shows a picture of the movie, title, description/overview of the movie and two buttons to add to library and to watch movie(these features may come if i want to make the app more full), but for now these buttons just show a pop-up after pressed. At the bottom of the screen you can see movies that may interest you - meaning that they share the same genre of movie.
4. Basic dummy login screen that's just there :)
5. WOrking on implementing a trailer watching screen, so when the user wants to press play movie button, they get redirected to this screen where they will be able to watch a trailer of their desired film.
6. 
Wanted to test with android still using expo, but my old Galaxy S8 didn't seem up for the task, therefore all testing was done with an Iphone 13pro.

# To run application
Fork or just download the repository and navigate to ScriptXCinema directory
```bash
cd ScriptXCinema
```
*You must create a .env to store your own tmdb api keys to test out if the project works :)*

To test application i used Expo, which allowed me to test my project on my iphone as my android device was acting up for some reason.
To use expo for testing of the application, you will need to use this command and get the Expo Go app on your mobile device:
```bash
npx expo start
```

Scan the generated qr code on your device and it will open your expo app, with which you will be able to try out the application. 
If you need to test out a web version of this application, use this command:
```bash
npx expo start --web
```

Other commands:
```bash
cd ScriptXCinema
npm run android
npm run ios # you need to use macOS to build the iOS project - use the Expo app if you need to do iOS development without a Mac
npm run web
```

#Pictures
<li>
  <ul><img src="https://github.com/user-attachments/assets/42e0de3c-dbf0-4b09-ac08-4e4a9215d8b8" width="300" height="500"> <img src="https://github.com/user-attachments/assets/904e6ae4-aa45-4a93-b4fc-a139e28785b8" width="300" height="500"></ul>
  
</li>
<img src="https://github.com/user-attachments/assets/42e0de3c-dbf0-4b09-ac08-4e4a9215d8b8" width="300" height="500">
<img src="https://github.com/user-attachments/assets/904e6ae4-aa45-4a93-b4fc-a139e28785b8" width="300" height="500">

<img src="https://github.com/user-attachments/assets/b757524c-ef93-40ca-8d2e-2c24cac3d79b" width="300" height="500">
<img src="https://github.com/user-attachments/assets/30e40616-dd34-4e92-ab85-8ea13641f1ab" width="300" height="500">

<img src="https://github.com/user-attachments/assets/c70909f4-982f-40a2-83a6-24c5cf6626c7" width="300" height="500">
<img src="https://github.com/user-attachments/assets/592b22e2-9846-48bd-8e83-3b29517eff1a" width="300" height="500">

<img src="https://github.com/user-attachments/assets/97c44be1-dad6-4b2a-acbc-7c1521eb3428" width="300" height="500">
<img src="https://github.com/user-attachments/assets/b37aa5e2-862f-44a7-9698-2e85d692f7d7" width="300" height="500">



