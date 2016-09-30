# Tic Tac Toe

Android based Tic Tac Toe

## Goal

### Gameplay

2 players play Tic Tac Toe taking turns on the same device (no network-multiplayer, no AI).


### Target design

Feel free to give it any "game-like" 2D design.

## Environment

* [Android](https://developer.android.com/index.html)
  * Target SDK version 24
  * Minimum SDK version 21
* [Android Studio](https://developer.android.com/studio/index.html)


## Instructions

### Setup

1. Fork this project into your Github account
2. Clone fork on your machine
3. Start Android Studio and choosen `Open an existing Android Studio project`

### Run

1. Once opened in Android Studio you can choose `Run -> Run 'app'` from the main menu
2. You might connect your Android device or create a new emulator
  1. To create an emulator choose `Create New Emulator`
  2. Select a phone hardware configuration, e.g. `Nexus 5X` and choose `Next`
  3. Select an Android version which fulfills the minimum requirements and
     continue with `Next`. (You might need to download the image first by
     choosing `Download`)
  4. Complete the emulator by choosing `Finish`
3. Select your device or an emulator and choose `OK`
4. The build process will start should automatically open the app once finished.

### Test

* Detailed information about how to run the unit tests can be found in
  the [Android Studio Documentation](https://developer.android.com/training/testing/unit-testing/local-unit-tests.html#run)
* In a short: Right-click on the `com.neopoly.tictactoe (test)` entry in the
  project pane and choose `Run 'Tests in tictactoe'`


## Troubleshooting

### Emulator cannot be launched: "Failed to sync HAX vcpu context"

If you running on macOS or Windows and are using [Docker](https://www.docker.com) you must stop the
Docker's Virtual Machine before any emulator can belaunched.
