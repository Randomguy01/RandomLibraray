# Welcome to RandomLibrary!

This library is a set of utility classes and methods by **Randomguy01!** 


## Purpose

The goal of this library is to make programming in Android faster and easier and to remove boilerplate code. I hope to make starting a new Android project easier, no need to rewrite code from your last project. 

## Features
Below are descriptions of all current features.


### Lifecycle

The [Android Lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle) is super important and really cool, but honestly, I hate dealing with it. The [Lifecycle](https://github.com/Randomguy01/RandomLibrary/tree/master/RandomLibrary/src/main/java/com/random/randomlibrary/lifecycle) package contains a set of classes to internally deal with the lifecycle and storing and updating data. Extending [RandomActivity](https://github.com/Randomguy01/RandomLibrary/blob/master/RandomLibrary/src/main/java/com/random/randomlibrary/lifecycle/RandomActivity.java) and creating a [PersistableViewHolder](https://github.com/Randomguy01/RandomLibrary/blob/master/RandomLibrary/src/main/java/com/random/randomlibrary/lifecycle/PersistableViewHolder.java) will allow you to take advantage of the methods ```update()``` and ```save()```. ```update()``` is called after an activity has started or restarted and ```save()``` is called before an activity is destroyed. These methods allow you to easily save and retrieve data using a [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel).

### Network

Managing basic network events and retrieving information about the current network status is not that hard. But it could be easier! Use the [NetworkManager](https://github.com/Randomguy01/RandomLibrary/blob/master/RandomLibrary/src/main/java/com/random/randomlibrary/network/NetworkManager.java) class to simplify checking internet connection and listening for changes in the network connection. 

### EventBus (Beta)

Communicating between components of different types can be frustrating and require more effort than you feel like putting in. Save what little effort you have to use [RandomEventBus](https://github.com/Randomguy01/RandomLibrary/blob/master/RandomLibrary/src/main/java/com/random/randomlibrary/eventBus/RandomEventBus.java)! A singleton for communicating between any component. 

Note: This is a **BETA!**

### Keyboard
Working with the Android soft keyboard should be super easy but it's not. It's really weird and you're not sure why anything done was done the way it was done. The previous sentence makes more sense than working with the Android keyboard! Use [KeyboardUtilities](https://github.com/Randomguy01/RandomLibrary/blob/master/RandomLibrary/src/main/java/com/random/randomlibrary/keyboard/KeyboardUtilities.java) to simplify your code. 

## Libraries
Huge thank you to the libraries used in the creation of this project, none of this could exist without them!

[Google Guava](https://github.com/google/guava)

[Material Design](https://material.io/develop/android/docs/getting-started)