# EnergyHack
=====================================================

## Theme : _Encourage public transportation_

Transport-related air pollution and rising traffic congestion that define several metropolitan cities, 
such as Bengaluru, across the world cause immeasurable economic and environmental damage.
Apart from tackling issues of poor air quality and increasing safety hazards that result, 
public transportation can help reduce your stress levels too!

Prerequisites
--------------

- Android SDK v24
- Latest Android Build Tools
- Android Support Repository

Getting started
---------------

This sample uses the Gradle build system.

1. Download the samples by cloning this repository or downloading an archived
  snapshot. (See the options at the top of the page.)
1. In Android Studio, create a new project and choose the "Import non-Android Studio project" or
  "Import Project" option.
1. Select the `CurrentPlaceDetailsOnMap` directory that you downloaded with this repository.
1. If prompted for a gradle configuration, accept the default settings.
  Alternatively use the "gradlew build" command to build the project directly.
1. Add your API key to your app's `gradle.properties` file.
  (For information on getting an API key, see the
  [documentation](https://developers.google.com/maps/documentation/android-api/signup).)
  
  
### Gradle

```groovy
repositories {
    mavenCentral()
}

dependencies {
    compile 'com.google.maps:google-maps-services:(insert latest version)'
   
}
```

Support
-------

- Stack Overflow: https://stackoverflow.com/questions/tagged/android+google-maps

If you have discovered an issue with the Google Maps Android API v2, please see
the resources here: https://developers.google.com/maps/documentation/android-api/support

If you've found an error in these samples, please file an issue:
https://github.com/googlemaps/android-samples/issues

