# Visual-aid-for-the-blind
An ML based android application that detects objects in surroundings using a smartphone. This app converts the output to speech that can be understood by the blind.

PROJECT WORKFLOW :

![image](https://user-images.githubusercontent.com/72302390/166414057-b006e14e-e772-4157-a676-9861c9d71b8f.png)

TOOLS AND REQUIREMENTS :

-> VSCode code editor

-> Flutter sdk

-> Java jdk

-> Adroid studio - Android sdk

-> Emulator/ Physical device

-> Android environment specific to the android version

IMPLEMENTATION OF THE APP :

-> Base file - main.dart

-> Project flow has these files and folders

     -> gradle
     
     -> library
     
           -> UI
            
           -> tflite
            
-> User Interface :

     -> home_view.dart
     
             - contains TTS module
             
     -> Camera_view.dart
     
     -> box_widget.dart
     
-> Tensorflow Lite :

   The folder has the following files.

     -> Recognition.dart
             
     -> Classification.dart
     
     -> stats.dart
     
TEXT TO SPEECH :

-> Flutter text to speech plugin provides TTS (Text-To-Speech) Service.

-> A list of results with attributes like label, confidence is saved.

-> speak feature of TTS converts the label of objects from string to speech output.

ANDROID APP OUTPUTS :

![image](https://user-images.githubusercontent.com/72302390/166415064-3bb0eb46-cf9b-4215-b52d-a52693fbe346.png)

![image](https://user-images.githubusercontent.com/72302390/166415110-fc42a8d8-e561-4870-87d2-3936b16a417e.png)

https://user-images.githubusercontent.com/72302390/166415138-90059865-81a6-4841-a621-bec077168b66.mp4

CONCLUSION AND FUTURE SCOPE :

The android application takes inputs constantly from the surrounding, real time and detects objects. The labels of these objects are converted to speech.

Future Scope:

-> OCR conversion

-> Object position detection

-> Moving objects detection

-> Increasing number of object categories

-> Advanced detection like staircases

THANK YOU!
