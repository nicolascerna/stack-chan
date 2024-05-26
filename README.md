# Stack Chan
This is based on [AI StackChan2](https://github.com/robo8080/AI_StackChan2)

![Image1](images/image1.png)<br><br>

**Stack Chan Features**

* Uses the web-based VOICEVOX for speech synthesis.
* You can choose between "Google Cloud STT" or "OpenAI Whisper" for speech recognition.
<br>

Google Cloud STT is based on "MhageGH"'s [esp32_CloudSpeech](https://github.com/MhageGH/esp32_CloudSpeech/ "Title").<br>
For the wake word, we used "MechaUma"'s [SimpleVox](https://github.com/MechaUma/SimpleVox/ "Title") library.

---

### Items and Instructions Needed to Create the M5GoBottom Version of StackChan ###
Please refer to this.<br>
* [StackChan M5GoBottom Version Assembly Kit](https://raspberrypi.mongonta.com/about-products-stackchan-m5gobottom-version/ "Title")<br>

### Items Needed to Build the Program ###
* [M5Stack Core2](http://www.m5stack.com/ "Title")<br>
* VSCode<br>
* PlatformIO<br>

Please refer to the "platformio.ini" for the libraries used.<br>

---

### Setting GPIO Numbers for Servo Motors ###
* Around line 46 of the main.cpp file, set the GPIO numbers used for the servo motors.

### Usage Instructions ###

Please refer to this.<br>

* [AI_StackChan2_README](https://github.com/robo8080/AI_StackChan2_README/ "Title")
