# Aplicação AR Drone
Sources da aplicação android do parrot AR.Drone, esta aplicação será usada para estudos e testes, onde vamos modificar codigo para perceber o funcionamento da aplicação.

## Why this repo?

Parrot has dropped support for its ARDrone 2.0 (kind of).
The [Play Store app](https://play.google.com/store/apps/details?id=com.parrot.freeflight&hl=en) hasn't been updated since 2013.
There was an official SDK, but it is no longer available online on the [official developer page](http://ardrone2.parrot.com/developer-zone/).

Still it can be found (version 2.0.1 [here](http://forum.developer.parrot.com/t/whats-the-state-of-the-sdk-support-for-ar-drone-2-0-ardrone-sdk-2-0-1-tar-gz/314) for instance).
It contains the source files for the SDK and sample apps on various platforms.

Also, in the Android world, things have changed a lot since 2013.
Android Studio and Gradle have replaced the old Eclipse and Ant build system.
The Parrot SDK was based on this deprecated build system and we need an updated sample app.

**This repository aims at making the Parrot AR Drone 2.0 SDK widely available again.
It is primarily for Android developers.
