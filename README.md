# GameEnginesLab4

InputManager and SingletonGeneration are both Singletons

InputManager is a little more advanced as it handles the keyboard input and SingletonGeneration handles a single variable

Two actions are hooked to the same sound action

The level generation button (press q to enable moving the mouse) and the zipline action (yellow box, press f to use)

The level Generation button doesn't call the action but calls another function which in turn invokes the action of the soundclip

Lab Stuff contains the sound file and the SingleGeneration, the input manager gameobject contains the input component
and the player contains the playercontrols which has the ziplineaction call
