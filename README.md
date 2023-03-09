# Laugh-tor-App
An android app that helps to learn how to work with multiple buttons without calling onClickListener() for each one of them seperately.

I have used **MediaPlayer** class here to play the sounds of different actor. With the help of tag defined here for each button in xml, I can refer to the respective audio files (in raw folder) and pass it as a String in getIdentifier(). 

**NOTE** : Here I have made single instance of MediaPlayer for all the buttons, so once you played any one audio or clicked any button you have to wait for that audio to get over first before clicking or playing any other button.  
