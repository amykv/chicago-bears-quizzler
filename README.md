# ChicagoBearsQuizzler

ABOUT:

A simple quiz app for android that covers Chicago Bears trivia. Only true and false questions right now. 50 questions, more to be added later as the app develops. The user chooses an answer then goes on to the next question, whether they are right or wrong. The game keeps track of the user score. Once the quiz ends, an alert pops up displaying the final score for the user and the option to close out of the app. App was originally written in Java, but has now been partially updated to Kotlin. App was created to learn more about Android development using Java, although now it has Kotlin. Eventually will like to rewrite this to make it look cleaner.


Shows the use of the Model View Controller(MVC) design pattern.

MODEL- The business logic of the app. Holding data of the true/false questions.

VIEW- What the user sees on screen, buttons, images, score progress, etc.

CONTROLLER- The application logic. Manage flow of data to and from model objects and view layer. MainActivity is the sole controller. Typcially controllers are subclasses of Activity or Fragment.


Currently just one screen type, quiz starts automatically from question 1.


This app is mainly for Chicago Bears enthusiasts and NFL trivia fans. As it stands, there are no pure Chicago Bears quiz apps on the Google Play store.


INSTALLATION:

Fork it or import the zip file into Android Studio. Run it from an emulator or transfer it onto the users device.


SCREENSHOT:

<img src="https://raw.githubusercontent.com/amvitkus/ChicagoBearsQuizzler/master/Screenshot_20201118-231534.png" alt="drawing" width="250"/>




TO DO:

Will likely do another rewrite in Kotlin, MVC pattern. Make the app look cleaner and more professional.

Add more questions, maybe add multiple choice ones.

Add question timer. 10 seconds? New prototype build has a timer, but needs fixing. Currently removed.

Change background image. Maybe no image for background as text can be tricky to see. Maybe use a simple MaterialUI.

Screen rotation? Or keep it vertical only.

Add a menu system with simple statistics.

Add a restart button once app finishes.
